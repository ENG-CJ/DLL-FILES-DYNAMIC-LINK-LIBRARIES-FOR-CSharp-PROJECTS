# DLL--FILES-DYNAMIC-LINK-LIBRARIES FOR C# PROJECTS
DLL Files - files that you can use in your CSharp project and save a lot of time to do validations,message Popups and sql special operations. You Can Download All Files For Free ): 

# HOW TO ADD THIS  DLL FILES INTO UR PROJECT
1. <kbd>Right Click References In Your Project </kbd>
2. <kbd>Click Add References</kbd>
3. <kbd>Browse Dll File From Your Computer and select</kbd>
4. <kbd> Then Click Ok and Thats It</kbd>

# MessagesDLL   | First DLL File
This dll file helps you from redundance code for messageBox, use this file instead of using <kbd>MessageBox.show("","",MessaeBoxButtonts,MesageboxIcon)</kbd><br>
This file contains classes and methods that shows up Winform  messagebox popups<br>
<b>How to use<b><br>
after adding reference import the dll file into your code file by using this syntax <kbd>using MessageDLL</kbd> ( using DLL_FILE_NAME)<br>
then This file contains class named <kbd>Messages</kbd> And that class contains methods to use that methods first create instance of the class <br>
to create use this syntax <kbd> Messages msg = new Messages</kbd> <br>
Messages : The Class name <br>
msg : the object variable<br>
new Messages() : creates the instance of messages<br>
then  call the methods by using this syntax <kbd>msg.ShowInfo()</kbd> <br>
ShowInfo() method : is a method the display information message , this methods takes two argument one is a message and other is title you can ignore but 
by default is null if you use without params the message displays null content to diplay message with content provide params into method or instance 
by instance use this syntax <kbd>Message msg = new Messages("hello","This title"); msg.ShowInfo();</kbd> <br>
you can pass params to the instance or you can pass to the  method  use this synatx by method : <kbd> Messages msg = new Messages(); msg.ShowInfo("Hello","This Title");</kbd><br> Others same as this one . Good Luck ! ☺


