# 💠 Ubuntu Complete Command 🛅

**About It** ➤ This particular command is used in order to specify how arguments are to be completed by Readline. If no options is provided while running this particular command, existing completion are printed in a way that allows them to be reused as input.

⦿ Getting started with the complete command in **Ubuntu Terminal**, below we have its example here 👇🏻

```
complete
```

✐ Note : Remember this will provide you a list regarding all those services or functions that are being completed. Also don't try adding the args or options that are not under that categories defined below 🔊

## 🔌 How to get all Completed Command's Specifications ❓

✇ In order to get all the specified commands that are completed with their specified details we have a simple integrated argument regarding and it provides a list of specified commands with their services that have been executed successfully.

➱ Let's get the specified command syntax here ⌨️

```
complete -p
# or
complete
```

✐ Note : There is not at all difference in case of using either *complete* or *complete -p* in **Ubuntu Terminal**, also we can do the same with each other on usecase.

## ❇️ How to remove all Complete Services or Commands ❓

✇ Below we have the format or syntax for the command in order to learn, that how we can remove all the specified list of commands that have been executed successfully, also after this on using the **complete -p** command there will be not a single list available for finding the specified list of commands.

➱ Let's try using this command and also we will run the command for getting the list of services or commands specified.

```
complete -r
# checking the commands list now
complete -p
```

✐ Note : Remember that the list will not get shown in the **Ubuntu Terminal** after the removal of the command list.

## ❇️ How to apply completion on default or empty specified command ❓

✇ Now, if someone wants to apply for the completion of default or empty commands in case to fill the list for it, we can use the syntax given below in order to keep the list unempty.

➱ Not in order to keep it in a long format let us just keep the command for initial, default and empty compeletion specification at single format only that is been given below 🔊

```
# running all the commands at once
complete -D && complete -E && complete -I
```

## 🪄 Specified Arguments Explanation 🖥️