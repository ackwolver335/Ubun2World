# 💠 Ubuntu Bind 🛅

**About IT** ➤ This command in **Ubunut Terminal** is used in order to bind a particular key or key sequence towards a readline function or method, or to set a readline variable. Regarding this command we have further different options to be used for its execution regarding specific purpose.

⦿ In other words, it allows us to change or display the key bindings, and these are associated with the key combinations that are pressed for performing specific actions over to the shell, where we used to run the commands.

➱ Let's get started having a look on its syntax in the most simpler way, in order to keep in mind for Ubuntu's Beginners.

```
bind [-lpsvPSVX] [-m keymap] [-f filename] [-q name] [-u name] [-r keyseq] [-x keyseq:shell-command] [keyseq;readline-function or readline-command]
```

## 🪄 Arguments Overview ⌨️

| 🕹️ **Arguments** | ➪ **Use Case** |
| ---------------- | -------------- |
| **-m keymap** | ⤐ It uses **KEYMAP** as the keymap for a particular duration of this command. The Keymap names which are acceptable are **emacs**,**emacs-standard**,**emacs-meta**,**emacs-ctlx**,**vi**,**vi-move**,**vi-command** and **vi-insert** |
| **-l** | ⤐ Used to get the list of available **functions**. |
| **-P** | ⤐ Shows the **functions** names together with their **bindings**. |
| **-p** | ⤐ It is used to get the **functions** and **bindings** in a format that can be reused as input. |
| **-S** | ⤐ Shows the key sequence that invokes **macros** and their **values**. |
| **-s** | ⤐ Used to list key sequence for invoking **macros** and **values** in a format that can be reused as an input. |
| **-V** | ⤐ Shows the name of **variables** and their **values** in a list format. |
| **-v** | ⤐ Lists the **variable's** names and their **values** that can be reused as an **input**. |
| **-q function-name** | Used for providing **query** about the keys that invoked that particular function. |
| **-u function-name** | ⤐ It is used for **unbinding** all the keys which are bounded to the named function. |

## ❇️ Bind [--Options] Overview 🕹️

✇ Using these particular options with this bind command is helpful in **Ubuntu Terminal**, as we uses these optional for specified purposes and also for fidning the methods or variable associated with specific key-sequences.

➱ Let's now get the details regarding the available function's name in the form of list. And the syntax for it is given below !

```
bind -l
```

✐ Note : In this similar way we can use the above command in order to get the details regarding commands and options explained above.

## 🔌 How to find functions and variables of binding keys in Terminal ❓

✇ Getting details regarding functions and variables together by the key shortcuts or key sequences that are binded together with them, are as simpler than your thoughts your are wishing to them as harder.

➪ Let's explore the function's name first together with their binded keys, with the command shown below 🔊

```
bind -P
```

➪ Also we can do the same with the variables and their details inside the **Terminal** in order to get available details 🫣

```
bind -V
```

✐ Further more options can be used in the similar format and also we can use them with the help of **Table** given [above](#-arguments-overview-️).

## 🔌 How to install bind command ❓

⦿ In case you don't have bind command in your installed **Ubuntu Terminal** you need to install it, and for installation regarding this command we further have different methods, either we may install it through **apt** or through **yum**.

➱ Let's install bind command using **apt** with the command given below ⌨️

```
sudo apt-get install bind9
```

➱ Let's install bind using **yum** command on the place of **apt** ⌨️

```
sudo yum install bind
```

🖱️ Apart from all of this, we further have another command regarding installation of this using **Source Code** and below we have specific commands for their installation.

```
wget http://ftp.isc.org/isc/bind9/9.11.2/bind-9.11.2.tar.gz
tar -xvf bind-9.11.2.tar.gz
cd bind-9.11.2
./configure
make
sudo make install
```

## 🔌 How to install Specific Version of bind command ❓

✇ Regarding installation of this command at a specific version we have different commands, below we have different methods or subcommands to be used in order to install bind command of **Specific Version** in your **Ubuntu Terminal**.

➱ Installation of **bind** using **apt** command.

```
sudo apt-get install bind9=9.11.3-1ubuntu1.12
```

➱ Installation of **bind** using **yum** command.

```
sudo yum install bind-9.11.3
```