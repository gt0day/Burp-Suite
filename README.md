# Burp Suite Professional Activation

## Requirement
- Java
- Burp Suite Professional (JAR)

> Download From [Here](https://portswigger.net/burp/releases#professional 'Burp Suite')

> Watch How To Activate On Linux [Here](https://www.youtube.com/watch?v=fuU2VwinlX4)

## Linux
- [1] - java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:PATH/loader.jar -noverify -jar PATH/burpsuite_pro_v2022.*.*.jar &
- [2] - java -jar keygen.jar
- [3] - Activation
	* Modify License String like "license to Siddharth"
	* Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
	* Select Manual Activation Option on your bottom Right in Burp Suite Pro.
	* Copy License Request from BurpSuite_Pro and paste in keygen.jar
	* Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
- [4] - Shortcut
  * With Sudo Permissions, Create a file with command "nano /bin/burpsuite-pro"
  * Paste command in text editor "java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:PATH/loader.jar -noverify -jar PATH/burpsuite_pro_v2022.*.*.jar &"
  * Change Permissions for files with command "chmod +x /bin/burpsuite-pro"
  * For Executing Burpsuite Write burpsuite-pro in Terminal and press Enter.
	
## Windows
- [1] - java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"PATH\loader.jar" -noverify -jar "PATH\burpsuite_pro_v2022.*.*.jar"
- [2] - java -jar keygen.jar
- [3] - Activation
	* Modify License String like "license to Siddharth"
	* Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
	* Select Manual Activation Option on your bottom Right in Burp Suite Pro.
	* Copy License Request from BurpSuite_Pro and paste in keygen.jar
	* Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
- [4] - Shortcut
* Open Notepad and Paste command at 2.1 and save the file with name burpsuite-pro.bat in PATH\Burp-Suite Folder.
* Open another Notepad and Paste below command and save it with burpsuite-pro.VBS extension in Desktop.
		Set WshShell = CreateObject("WScript.Shell")
		WshShell.Run chr(34) & "PATH\Burp-Suite\burpsuite-pro.bat" & Chr(34), 0
		Set WshShell = Nothing
* For Executing Burpsuite Double Click on burpsuite-pro.VBS file.
