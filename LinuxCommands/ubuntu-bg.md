# 💠 Ubuntu bg/jobs 🛅

**About IT** ➤ This command in **Ubuntu Terminal** is used in order to check the working jobs, that are currently in progress or process status. And we can also see details about the particular working job which is in progress.

⦿ It is a command or process non other than stop/suspend the execution of processes or jobs or continue their execution as per their requirements. This is done by using Operating System and shell such as bash/ksh or POSIZ Shell. It `bg` command is part of Linux/Unix shell job control.

➱ Let's get started by exploring the Syntax of the bg command and learning its use.

```bash
# bg job_ID
#bg job_ID1 job_ID2
```

## ❇️ How to find current Job Status ❓

✇ Searching for current job status or session is so simple from your thoughts or expectation, also here we have another command for checking the concept of current job status or session, below we have the syntax for it.

```bash
jobs
# or 
jobs -l
```

✖ Note : Please don't use any particular command while you have used any job session/process in execution otherwise you may face many kinds of errors.

➱ When you would use the above command as per the syntax, you would surely find the list of the available jobs currently in execution or working states. For initiating or starting any particular job session, you must need to type the name of job for running it.

➱ Let's understand by running a particular jobs, say for we found a job with name **gnome-calculator** and we want to run it,

```bash
bg %2
```

➱ In the command above **%2** refers to the 2nd job in the list of jobs.

## ❇️ How to Suspend particular Job Session/Status ❓

✇ In simple words, a job that is currently running can be easily suspended by using `Ctrl+Z` shortcut key/sequence and we have an alternative regarding this, that we can use the `kill` or `pkill` command in the way mentioned below to stop any job session.

```bash
# kill -s stop PID
# kill -s stop jobID
# pkill -stop PID
```

✐ Note : Remember to use the command after removing the `#` from its starting and replacing the `jobID` or `PID` from the job list, otherwise the commands provided would not work properly.

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿