# 💠 Ubuntu Alias 🛅

**About It** ➤ This command in Ubuntu Terminal is used in order to check the available alias names, and another use of this command is to create/defines an alias in the Terminal.

➪ In simple words, we can understand it as, it is used simply in order to create our own commands for linux terminal to be used instantly.

➪ Run the command given below to check the available aliases on your devices.

```
alias
```

➪ Command given below works similar to above, one but have the difference of preference. As here we uses **-p** for getting all the available aliases in Ubuntu Terminal.

```
alias -p
```

## ✴️ Creating an alias 🖱️

⦿ Let us create our own commands with the help of linux **alias** command, but before which let us first review its syntax.

```
# alias command_name='linux command to be used'
```

⦿ First, we need to open the linux terminal with the command **Ctrl + Alt + T** and then I m going to create an alias for opening my **Downloads** folder directly with simple keywords.

➪ I m going to create a command **cdDown** for opening **Downloads** folder directly. So, follow the syntax carefully.

```
alias cdDown='cd Downloads'
```

✖ Note : Remember to use the commands at the initial locations, only where you have initiated them, otherwise you may face some errors there.

➪ Surely, after running the command from the location you've created it, you will redirect to your Downloads folder without any kind of error. Also you may check, if the commands are available in the alias section or not by using the **alias** command.

## ❇️ How to Remove any alias, if created ❓

✇ Hope after learning, how to create an alias in **Ubuntu Terminal** you would have created and tried a lots of aliases in your terminal. Let's now delete those aliases which you don't want to be in your list of aliases.

⦿ Deleting an alias in **Ubuntu Terminal** is so simple, as you think for your first time to be harder, below we have syntax for deleting an alias name that is no longer required for further usage.

```
# unalias alias_name
```

➪ So, after getting the syntax let us simply delete that particular alias that we have created for learning alias creation.

```
unalias cdDown
```

✐ Note : When you would search your alias that you have recently deleted you would surely found that it is not available in the list, which you may check with the command **alias** or **alias -p**.

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿