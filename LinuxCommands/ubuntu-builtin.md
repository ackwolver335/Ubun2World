# 💠 Ubuntu Builtin 🛅

**About It** ➤ This command in **Ubuntu Terminal** is been used in order to execute **shell builtins**, and it executes the shell-builtin with the required arguments *without performing the command lookup*. Here, it simply means that the command will be surely executed but there would no message or changes will occur in the GUI Interface.

➪ In simple words, the command will be executed in the background of the **GUI Interface** that you're using in **Ubuntu Terminal**.

➪ Let's run the command and see what happens, as there is no change in the UI on its execution.


```
builtin
```

**General Definition** ➤ builtin command is used to run a shell builtin, passing it arguments(args), and also to get the exit status. The main use of this command is to define a **shell function** having the same name as the shell builtin by keeping the *functionality* of the builtin within the function.

```
builtin ubuntu_command_here
```

✐ Note : The builtin command directly redirects to the shell available in your **Ubuntu OS**, so be carefull while using it with its syntax as one wrong syntax can cause a lot of damage to software and internal codes.

## ❇️ How to define shell function using builtin ❓

✇ In order to define a shell function with the help of builtin command, we can do it with so easier steps just by using the syntax as it is given below we can define it as per our own needs and requirements. But would only works with the pre-defined keywords of **Ubuntu Terminal**. Below we have further code explanation.


```
cd()
{
    builtin cd Documents
}
```

❌ Note : Remember to use this method or format on that particular command which you don't uses continuously otherwise you may get stucked in the **Terminal**, and also if you don't find any idea close the **Ubuntu Terminal** and open it again.

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿