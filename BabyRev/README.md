# BabyRev - Writeup

## Description

![Alt text](img/1.png)

![Alt text](img/2.png)

## Solution

In this challenge i simply opened the binary inside IDA pro and after doing some static analysis i figured out that the binary asks for a password and a secret code which are `Sup3rS3cr3tP455W0rd` and `1337` .

Note : we can use `[https://dogbolt.org/](https://dogbolt.org/)` also for decompilation instead of IDA pro.

![Alt text](img/3.png)

After a successfull input we got our flag .

![Alt text](img/4.png)
