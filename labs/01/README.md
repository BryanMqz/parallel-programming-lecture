# Lab 01 instructions

## Objective

Make the students get familiar with the operating system tools to:

* Compile from the command line
* Configure SMPT server to do git send-email

# Requirements

* Linux machine, either a VM or a baremetal host
* GCC compiler (at least version 4.8)
* shell scripting
* git send mail server installed and configured on your Linux machine

## Instructions

* Clone the repository
* Change your name in the code
* git add hello.c
* git commit -s -m 'ITESMID-homework-01'
* git send-mail -1

## Expected result:

```
/* Hello World program */

#include <stdio.h>

int main(void) {
    printf("Hello World\n");
    printf("My name is Student Name \n");
    return 0;
}
```

## Please send the mail as git send mail or git fork:

```
    $ git add hello.c
    $ git commit -s -m <STUDENT-ID>-homework-01
    $ git send-email -1
```

Do some tests sending the mail to your personal account, if you get the mail,
then you can be sure I will get the mail

# Time to do the homework:

    One week from the moment the mail is sent to students

