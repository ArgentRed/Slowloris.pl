# Slowloris.pl
**ABSTRACT:**

Slowloris.pl perl denial of service (DOS) program originally created by RSnake, modified by ArgentRed.

---

**OVERVIEW:**

This guide is written in such a manner that the program can be executed by anybody to launch a DOS attack against a target. Some steps may be unnecessary if the user already has Perl installed onto their computer, however Perl & slowloris.pl can be put onto a flashdrive and any computer can be used as a launchpad for a DOS attack following these steps:

**REQUIREMENTS:**

-	slowloris.pl
-	Perl
-	Terminal
-	An internet connection
-	A target

**BASIC STEPS:**

1)	Download Perl

2)	Download slowloris.pl

3)	Open terminal

4)	Enter 'set PATH=[drive letter of drive with Perl]:\[Perl folder name]\bin;%PATH%'

*EXAMPLE:*    'set PATH=C:\Perl64\bin;%PATH%'

5)  Enter '[path to perl.exe] [path to slowloris.pl]' into terminal and hit enter

*EXAMPLE:*    'C:\Perl64\bin\perl.exe C:\User1\Documents\slowloris.pl'

6)	Follow on-screen prompts from slowloris.pl in the terminal

*NOTE:* You only have to do these steps once!

**CREATING A SHORTCUT:**

Because it's more convienent this way.

1)  Right click on desktop.

2)  'New' -> 'Shortcut'

3)  Paste '%windir%\system32\cmd.exe /k [LOCATION OF PERL.exe] [LOCATION OF SLOWLORIS.PL]

*EXAMPLE:*      %windir%\system32\cmd.exe /k C:\Perl64\bin\perl.exe C:\Users\User1\Documents\slowloris.pl
