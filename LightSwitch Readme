# Lightswitch 2015
1/20/17

**Todo:**  
1. Done. Add refresh code when adding new receipt detail record.  
2. Done. Can't edit the parent as well after editing details update  
3. Remember to apply labels as needed in TFS  
4. Checkout image-uploader.js  
5. blogs.msdn.com/lightswitch  
6. hands-on lab  

# Articles
[Enabling Authentication](https://msdn.microsoft.com/en-us/library/ff851984.aspx)

[StackOverflow article](http://stackoverflow.com/a/6290358)  
[Article 2](http://lightswitchhelpwebsite.com/Blog/tabid/61/EntryId/1208/New-API-For-Refreshing-Data-in-LightSwitch-in-Visual-Studio-2013.aspx)  

# Excellent Videos
[Building Business Apps](https://channel9.msdn.com/posts/Building-Business-Applications-with-LightSwitch-for-Visual-Studio-2012)  

LightSwitch HTML5 Demo  
[https://youtu.be/tu5G8AsOlr0](https://youtu.be/tu5G8AsOlr0)  
Very complete demo   
deploying  
javascript code  
missing parent child navigation client screens  


[https://youtu.be/oIBJrGp-kOY](https://youtu.be/oIBJrGp-kOY)  
This one takes care of the parent child navigation


# Code Notes
**.lsml** stands for Light Switch Markup Language


**Default date for new receipt**  
See Receipt.lsml.js file  
Steps:  
1. Went to Receipts.lsml  
2. Clicked on Html Client perspective  
3. Clicked Write Code arrow down  
4. Selected created handler 
5. ```entity.DatePurchased = new Date()```   


**Set focus on textbox**  
[MSDN Thread](https://social.msdn.microsoft.com/Forums/vstudio/en-US/b14793f0-a1f8-483b-b017-5bbed62a598e/setting-focus-on-textbox-control-in-lightswitch-html-client?forum=lightswitch)

# Deployment Notes

Deploying LightSwitch

Make sure VS start as administrator

Create SQL Logins  
IIS APPPOOL\DefaultAppPool  
TestUser (only if using Forms Auth)  


LightSwitch on MSDN  [[Go]](https://msdn.microsoft.com/en-us/library/ff852001.aspx)  

6:32 PM 1/21/2017  
Deploying LightSwitch [[Go]](https://youtu.be/pzw7sRsjT2o)
* Shows windows and web deploy
* 14:45 Starts web portion


SQL Browser Services (make sure enabled in services)  
Enable Named Pipes 2x  
Restart SQL Services
Make sure in mix mode

Install Web Deployment Tools
(Check services for Web Deployment Agent)  

**Caveats**  
Had to create the iis application manually and then deploy
