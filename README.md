# AccessIdracPortable
Access Dell iDrac Portable

Easily access the old Dell iDrac virtual console using non-installed portable versions of Firefox v.25 and Java 6.

The complete files and structure are stored in a zip in the "complete_install" directory.

The zip is packed using absolute pathnames. So it will create the "C:\temp\AccessIdracPortable\" folder structure.
1. Using 7-zip
2. Use "Extract Files ..."
3. Change "Path mode:" to "Absolute pathnames"
4. Will create the "C:\temp\AccessIdracPortable\" folder structure.

Files obtained from (if you want to dl and build yourself):
https://sourceforge.net/projects/portableapps/files/Mozilla%20Firefox%2C%20Portable%20Ed./Mozilla%20Firefox%2C%20Portable%20Edition%2025.0.1/
https://sourceforge.net/projects/portableapps/files/Java%20Portable/Java%20Portable%206%20Update%2022/

Found another way to make things even easier. Here we are going to set the Java Web Start Launcher portable as the default program to launch, inside of Firefox v.25. All other browsers will be unaffected.

1. Open Firefox v.25
2. Open the Firefox menu
3. Click on "Options"
4. Click on "Options". (Yes there are 2 of them)
5. Click on "Applications"
6. Scroll down to "JNLP File"
7. Click on the drop down for "JNLP File". Should be on "Always Ask".
8. Click on "Use Other ... "
9. Click on "Browse..."
10. Navigate to where you store "javaws.exe". If you use the zip file and maintain the directory structure, then it will be "C:\temp\AccessIdracPortable\Java\bin\javaws.exe"
11. Click on "OK"
12. Done !

