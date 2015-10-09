What is Vault?
==============

Vault is a minimalistic password manager for hackers. It takes out all the flair and complexity that comes with traditional password managers and condenses the idea into a simple commandline 
interface. Vault can be deployed anywhere Python is installed. Vault does not use any third party dependencies which means all you have to do is clone this repo to get started. Simply clone 
the repo and run vault.py.

Why use Vault?
==============

In todays world it is important to have a different password for each of the different services that we use in our every day lives. Unfortunately, managing a lot of different passwords is hard.
There are solutions out there that try to solve the problem, but they are all bloated and seem to do the job too well at times. Vault is not for those who want flair, or fancy user interfaces. Vault
is for hackers, people who live in the terminal. Vault takes out all of the complexities that are present in other technologies and condenses them into three basic concepts, encryption, password
stores with a database, and easy lookup. That's it. That's all we want it to be. 

How does it work and how do I get started?
=====================

Getting started with Vault is very easy. Simple clone this repo and run vault.py in the directory of your choosing. If Vault does not detect a file.db file in your current directory it will
create one and ask you for a new password. This password will be the master password that is used to encrypt your data. Vault uses the aes module from the SlowAES project, we have not written our 
own implementation. Every time Vault is run you will be asked to insert this master password in order to access your data. If you forget the master password all the data will be lost.

What are the features of Vault?
===============================

Vault provides the very basics of storing passwords and keeping the data safe.

- AES Encryption
- 30 second inactivity timeout
- Password labels
- Password lookup
- Simple commandline interface

What are the commands in the Vault shell?
=========================================

* read - This will return all the passwords stored in plain text
* add - This will bring up the prompt to add a new password
* remove - This will give you the prompt to remove a password
* search - This will give you the prompt to search for a password
* exit - Safely exits Vault

How can I contribute?
=====================

Easily! Just fork the repo and push your change. It will be reviewed and if it's something we feel will help Vault then we will merge it.

