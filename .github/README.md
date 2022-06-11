# JVM-Bytecode Emulator (WIP)
This is the repository of my JVM bytecode emulator for reverse engineering purposes, developed in Java. This emulates Java instructions with debugging functions including memory manipulation etc. Funnily enough, the complete emulation is written in the Java programming language and you can also claim that this is its own JVM. All information regarding the instructions I got from [Wikipedia](https://en.wikipedia.org/wiki/List_of_Java_bytecode_instructions).

## Developer
In this chapter I give all the information a developer needs for further development of the project and for pull requests.

### Contributions and Issues
Contributions are welcome in principle. Since I am busy, I will not be able to merge all of them directly. Probably I will not accept all of them. If this is the case, I will possibly leave a detailed reason. However, if you are not interested in further development but just want to leave a suggestion, you can use the [issue](https://github.com/Cach30verfl0w/JVM-Bytecode-Emulator/issues/new) function.

### Build this project
```
$> git clone https://github.com/Cach30verfl0w/JVM-Bytecode-Emulator.git
$> cd ./JVM-Bytecode-Emulator
$> gradlew clean build
```

## Story behind this
I'm doing challenges on [TryHackMe](https://tryhackme.com/p/Cach30verfl0w). There I found the [JVM Reverse Engineering](https://tryhackme.com/room/jvmreverseengineering) challenge and got a bit stuck on Task 6 and remembered that I don't have a reverse engineering tool for Java. Now I am developing such a tool, customized to my liking and evolvable. And because others could use something like this, I thought about making the source of this tool public.

## License

Since I see quite a lot of value in this project for me, and it's also important to me that the license is a bit tougher on a project like this, I'm going to use the [LGPL-2.1 (GNU Lesser General Public License v2.1)](https://github.com/Cach30verfl0w/JVM-Bytecode-Emulator/blob/main/LICENSE) license. And here I explicitly ask that this license and my work be treated respectfully and not simply taken, gerenamed and then published or sold etc.
