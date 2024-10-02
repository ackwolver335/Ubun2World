# 💠 Ubuntu dirs Command 🛅

**About It** ➤ In **Ubuntu Terminal**, the dirs command is used in order to get the stack of directories. And this command is been used in order to display something. It generally displays the list of currently remembered directory. Also the directory find their way onto the list with the `pushd` command, you can get back up through the list with the `popd` command.

⦿ Before getting started with the command, let us first get into the related information regarding the **Syntax** for it.

➱ Let's get enrolled in the syntax here, which is given below.

```
dirs [-clpv] [+N] [-N]
```

## ❇️ How to use dirs for Basic Functioning ❓

✇ In order to start using the **dirs** command it is used for performing basic methods, in order to use the proper methods and proper syntax also the working methods for getting the data or directory displayed. Below we have the syntax regarding it.

```
# getting the general location first
dirs

# getting the data regarding current folder or directory
dirs -c
```

✐ Note : Regarding the data or proper **options** or **args** to be used in order to get other details to be displayed.

## ❇️ How to use pushd and popd for Getting Stack Displayed ❓

✇ These are some different command's syntax to be used together with the initiation of the **pushd** and **popd** as these are used in order to add the data to the stack which is been shown in the **Terminal** which is been shown.

➱ Let's understand the details about the command now, with the syntax given below.

```
# pushing the detail below in a particular folder
pushd /etc

# again adding another tray in the stack list
pushd /dev

# removing the first stack element now
popd
```

## 🔌 Args/Options with dirs Command 🖥️

🖱️ Arguments and Options are necessary in order to use the **Terminal** commands in different ways and get different details or information from it, below we have different arguments or options in the form of tabular content or tabular format.

| 🎁 **Options** | 📑 **Information and Usage** |
| ---------------- | ---------------------------- |
| **-c** | ✔ It is used with the **dirs**, it clears the directory stack's element or all stack's element there. |
| **-l** | ✔ It do not print tilde-prefixed versions of directories relative to your home directory. |
| **-p** | ✔ It is used when we need to print the directory stack with one entry per line. |
| **-v** | ✔ It works similar to **-p** together by adding prefix with the position in the stack. |

➱ Also remember that these options can generally be used in order to check the stack list or data to be displayed. And related to this we have the code syntax to be used in order to get these options and arguments used.

```
# checking the single line stack format to be displayed
dirs -p

# Using the overall data to show the overall stack
dirs -l
```

| 🎁 **Arguments** | 📑 **Information and Usage** |
| ---------------- | ---------------------------- |
| **+N** | ⌨️ Displays the Nth entry counting from the left of the list shown by dirs when invoked without options, starting with zero. |
| **-N** | ⌨️ Displays the Nth entry counting from the right of the list shown by dirs when invoked without options, starting with zero. |

✖ Note : While using the **dirs** command, please don't use these argument alone-side without the options.

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿