# 💠 Ubuntu Case 🛅

**About It** ➤ The bash case statement is generally used to simplify complex conditionals when there are multiple different choices. Using the case statement instead of nested if statements will help make your bash scripts more readable and easier to maintain.

⦿ The Bash case statement has a concept similar to the Javascript or C switch statement. The main difference is that, unlike the C switch statement, the Bash case statement doesn’t continue to search for a pattern match once it has found one and executed statements associated with that pattern.

## 🔌 Case Statement Syntax ⌨️

➱ The syntax of the Bash case statement consists of the “case” keyword followed by the value to be matched, the “in” keyword, and one or more patterns with corresponding code blocks enclosed in “;;” statements:

```
case EXPRESSION in

  PATTERN_1)
    STATEMENTS
    ;;

  PATTERN_2)
    STATEMENTS
    ;;

  PATTERN_N)
    STATEMENTS
    ;;

  *)
    STATEMENTS
    ;;
esac
```

## 🖥️ Key Concepts of Case Statement 🖱️

- 🎯 Each case statement starts with the case keyword, followed by the case expression and the in keyword. The statement ends with the esac keyword.

- 🎯 You can use multiple patterns separated by the | operator. The ) operator terminates a pattern list.

- 🎯 A pattern and its associated commands are known as a clause.

- 🎯 The commands corresponding to the first pattern that matches the expression are executed.

- 🎯 It is a common practice to use the wildcard asterisk symbol (*) as a final pattern to define the default case. This pattern will always match.

- 🎯 If no pattern is matched, the return status is zero. Otherwise, the return status is the exit status of the executed commands.

## ❇️ Where/How to use Case Statement ❓

✇ Case Statement or any other statement which is inbuilt with the shell commands are used either inside the **.sh** extension containing files or other files that are used and run at the time of Startup Application or initiating of loaders in the **RAM**.

➱ Let's understand this with the help of an example and run the code within the **Ubuntu Terminal** in our OS.

```
#!/bin/bash

echo -n "Enter the name of a country: "
read COUNTRY

echo -n "The official language of $COUNTRY is "

case $COUNTRY in

  Lithuania)
    echo -n "Lithuanian"
    ;;

  Romania | Moldova)
    echo -n "Romanian"
    ;;

  Italy | "San Marino" | Switzerland | "Vatican City")
    echo -n "Italian"
    ;;

  *)
    echo -n "unknown"
    ;;
esac
```

✐ Note : Remember to use it within the Ubuntu after saving in a particular file with extension **.sh** and don't try using this with the system files with the same extensions otherwise you may face different problems while running your **Ubuntu OS**.

➪ For running the file in **Ubuntu Terminal** you need to running the following command.

```
bash file_name.sh
```

### 🔅 Conclusion 💻

🖱️ By now, you should have a good understanding of how to write bash case statements. They are often used to pass parameters to a shell script from the command line. For example, init scripts use case statements to start, stop, or restart services.

## 📑 Feeback Request 🔍

➱ Everyone, visiting these helpful notes or information, its owner's humble request to please provide the feedback in the Discussion Page of our Repo for making more better improvement in our learning Resources.

➱ [Click](https://github.com/ackwolver335/Ubun2World/discussions) here to visit the **discussion center**.

➱ Thanks for visiting my Repository, hope you find it useful. Let's [connect](https://github.com/ackwolver335) and collaborate for building 🏗️ something amazing 🗿