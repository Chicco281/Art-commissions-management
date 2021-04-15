Things you need to know in order to use this program
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
DON'T FUCKING TOUCH SETTINGS.TXT OR YOU WILL DESTROY EVERY SINGLE PIECE OF THIS APP. thx
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

--=More things you need to know:=--

1) notifications.exe is used to send.. well.. notifications. If you want to automatize the process you need to set up a task using "task scheduler".
2) If you want to test the notification, run it! If nothing happens, then open settings.txt and check if on line 2 there's "no_not" or it's blank. Otherwise there's a bug. In order to help me do this:
1- Press WIN+R and type in CMD
2- Type in: cd [path to the folder containing the files]
3- Type in: notifications.exe

If you see some strange stuff such as "Traceback: Most recent call....." then send me a screenshot or the whole text. Otherwise if nothing happens re-read step 2.

3) When you run the program a CMD will pop-up everytime (the black window). It's normal and closing it will close the other program too. If on that black screen you see something like ["stuff", "more stuff"] or "False" then I'm fucking stupid and I forgot to remove a debug statement. Please report it to me.


--=What does every file do?=--
[Commissions UI.exe] = The program used to manage all your commissions. Just run it to see what it does
[notifications.exe] = The program used to send  windows notifications.
[commissions (folder)] = Here all of your commissions are stored. They are stored as a *.pkl file. You can't open them unless you know how to decrypt it :)
[settings.txt] = As I already said, this file is important. If you don't touch it then everything is going to be fine. But modifying anything inside can lead to some annoying errors. If something goes wrong delete the content, but before doing it, send me the content of that file and the informations I need (Such as when does it happen, after what etc..).
[money.txt] = Keeps track of all the payments


--=--= CHANGELOG =--=--
Version [2.1.0]
-Added changelog to the README.txt
-Added money feature. Now you can keep track of the total income, the highest and the lowest payment received and total income by completing all commissions.
-Added "money.txt" file.


--=Some technical stuff=--
Imports used: PySimpleGuI - plyer - os - datetime - pickle
Modules used: 4
Total lines: 423 (for now)

