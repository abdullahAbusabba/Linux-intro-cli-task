# Linux-intro-cli-task


## Tasks:

-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> whoami                  
abdullahabu-sabba
```
-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.

```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> hostname                
Abdullahs-MacBook-Pro-2.local
```
-	Use history command and run one of the processes that appears in the history without re-write the command?
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> history !1                                                        
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> history pip install -pandas

```
-	Find since when your system was running?
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> uptime                  
18:44  up 33 days, 10:39, 2 users, load averages: 1.87 2.52 2.89
```
-	Get the data and time in Dubai using CLI?
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> TZ=Asia/Dubai date
Tue Jan 17 19:45:01 +04 2023
```
-	Store calendar output to a file called calender.txt
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> cal 1> calender.txt 
```
-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> echos “Oh there is an error” 2> logs.txt
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> cat logs.txt 
zsh: command not found: echos
```

## Additional Challenge:

-	Count how many words in any file in your system?
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> grep -o -i lamb count_words.txt | wc -l
       2
 ```
-	Find the logged in users in your system?
```
┌[kiwish-4.2]-(Downloads/Linux-intro-cli-task-main)-[git:master*]-
└> users 
abdullahabu-sabba
```

## Submission:

- After finishing the task take screen shot of the script and the output after run the script.
- Then upload the pictures to the forked repo and then create a pull request.



**Always remember to use man command to explore the commands you are using!**



