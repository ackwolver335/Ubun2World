# 💠 Ubuntu compopt Command 🛅

**About It** ➤ It is used in order to execute a particular process asynchronously, And this is done with the standard output and standard input of the command connected via a pipe to file descriptors assigned to indices 0 and 1 of an array variable NAME in the executing shell.

⦿ An interesting fact about this particular command is that it's default name is **COPROC**, which is been shown on running every particular command, that is been used after creating them and running in order to check its working procedure.

➱ Let's get mix up with it by running its basic format of command and also getting what happens afterwards.

```
coproc [name_here] command_of_ubuntu [redirection_of_commad]

# further different format of it
coproc command args #first command
coproc name command args #second command
```

✐ **Further Information** ➵ coproc command in Linux is a shell command which allows us to create a co-process that is connected to the invoking shell via two pipes. One of the pipes enables us to send the input while the other enables us to read the output without having to resort to named pipes. The co-process is executed asynchronously in a subshell. This command can be used above bash versions 4.0.

## ❇️ How to add data 🤔 or instruction to COPROC array HEAD ❓

✇ While this particular procedure of getting the instruction added in the **COPROC** array or in its head is too easier to get started with and this is done with the help of command structure that is been given below.

```
# getting the detail of pc or me
coproc (echo $(whoami))

# getting the detail of COPROC
echo "The Coprocess array is ${COPROC[@]}"

# Getting the PID of Coprocess
echo "The Coprocess PID is : ${COPROC_PID}"

# reading the data related to it
read -r o <&"${COPROC[0]}"

# time to get the ID here
echo "The user is $o which is the output of the coprocess"
```

✐ Note : On running the commands as it is, you will surely get the details regarding the one those are mention in it like, PID or Coprocess Array.

## ❇️ How to get 🤔 a whole string written with bash and COPROC Command ❓

✇ Here, we don't have to get confused about the task and getting the things done with the help of **COPROC** command, in order to do this we just need to follow the syntax given below and in some of those things we can also make some changes.

```
# getting the name defined first with the help of coproc command
coproc ackWolver { bash; }

# defining the characters at the first and its greater position
echo 'echo ackWolver' >&"${ackWolver[1]}"

# reading the data and defining a variable here to store it
read data1 <&"${ackWolver[0]}";

# getting the data variable to output it
echo $data1
```

✐ Note : By following the syntax given above you would surely have understood the use of **COPROC** command and its different advantages, also you wouldn't have found it to be so hard to get implemented.

## ❇️ How to work with 🤔 Instances in bash files with COPROC ❓