# 💠 Ubuntu cd Command 🛅

**About IT** ➤ If we talk about its main purpose, it is to change a particular directory to its sub-directory location, and this is useful if we want to execute a particular command at a specific location in the directory. Also we have further different options available regarding some different purpose with **cd** commands options which are optional in **Ubuntu Terminal**.

⦿ Below we have the simple use of **cd** command which is used to redirect the **Terminal** to its main location where all users important and working directories are available.

```bash
cd
```

## ❇️ How to use cd Command in Ubuntu Terminal ❓

✇ It is one of the simplest command to be used in **Ubuntu Terminal** and together with this its use is basic and simple that to change the current working directory.

➱ Let's have its syntax below to understand it.

```bash
cd sub-directory_name
```

✐ Note : Remeber to use the correct sub-directory name in order to get the current location of the **Terminal** to be changed, otherwise you may face error message regarding it.

## 🖥️ Different Uses of cd Command ⌨️

✇ Option or Details shown below are optional arguments that are not as much important to be used in **Ubuntu Terminal** while running cd Command in order to execute a particular operation or process. Also the main command and use of **cd** statement is already shown above.

➱ **-L** : This option with the **cd** command is been used in order to force symbolic links to be followed, another use is to resolve symbolic links in dir after processing instances of '..' Below we have an example for its better explanation.

```bash
cd -L symbolic_links
```

➱ **-P** : It works similar to *-L* on the place it follows the physical directory structure or location without following the available symbols in it. And resolve symbolic links in **DIR** before processing instances of '..'

```bash
cd -P symbolic_links
```

➱ **-e** : This option is used together with the above one, and if the current working directory is not supplied or is missing, it will exit with returning the status as **non-zero** status.

```bash
cd -P -e sub-directory_location
```

➱ **-@** : It works in some versions of **Ubuntu**, and where it works it returns the file with extended attributes as a directory containing the file attributes. Let's understand it with the syntax given below.

```bash
cd -@ sub-directory_name
```

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿