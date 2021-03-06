<link rel="stylesheet" type="text/css" href="http://cordova.apache.org/master.css">

<div class="grid leadin" style="">
    <div class="wrap">
        <img src="http://cordova.apache.org/images/cordova_bot.png" alt=""/>
        <ul class="text-block" style="font-size:280%;">
            <li><strong>Cordova OSX </strong><div class="t_ext-block" style="font-size:60%;">Plugin Templates</div></li>
        </ul>

		
    </div>
    
</div>

![image](https://raw.github.com/RandyMcMillan/cdv-osx-plugin-templates/master/ScreenShots/ScreenShot.png)


###Installation:

####`$ git clone https://github.com/RandyMcMillan/cdv-osx-plugin-templates.git`
>Clone the repository to your home folder ~/

####`$ ./installer install`
>The installer script creates symlinks to ~/Library/Developer/Xcode/File Templates 


![image](https://raw.github.com/RandyMcMillan/cdv-osx-plugin-templates/master/ScreenShots/ScreenShot5.png)

###Commands:

###`$ ./installer install` 
- Recursively initializes submodules (so you don't need to worry about it)! 
<br>
<br>

###`$ ./installer uninstall`
- This removes symlinks

>The repo will remain but the templates will not be visible in Xcode.
<br>

###`$ ./installer upgrade`
- pulls from repo and reinitializes submodules.

>Simplifies updating the templates for continued usability.<br>
>As new templates are added they will become visible in the Xcode new file dialogue.
<br>

###`$ ./installer help`
- List of commands in terminal .
<br>
<br>

###`$ ./installer readme`
- Open http://randymcmillan.github.com/cdv-osx-plugin-templates/ in browser. 
<br>
<br>



###The Xcode templates are in a form that is easily converted into a standard form that most @PhoneGap developers are familiar with.

#Steps to convert the templates into a familiar form



* Command+n in Xcode 

![image](https://raw.github.com/RandyMcMillan/cdv-ios-plugin-templates/master/ScreenShots/ScreenShot7.png)

* Select the plugin you want to convert to standard form

![image](https://raw.github.com/RandyMcMillan/cdv-ios-plugin-templates/master/ScreenShots/ScreenShot8.png)

* Save plugin where ever you prefer

![image](https://raw.github.com/RandyMcMillan/cdv-ios-plugin-templates/master/ScreenShots/ScreenShot3.png)

or to a location not in a Cordova Project

![image](https://raw.github.com/RandyMcMillan/cdv-ios-plugin-templates/master/ScreenShots/ScreenShot6.png)

* The plugin is now in a familiar format

![image](https://raw.github.com/RandyMcMillan/cdv-ios-plugin-templates/master/ScreenShots/ScreenShot9.png)

##Use the templates anyway you like. If you choose to redistribute the code then **you must** assume the responsibility of supporting your distribution. 

*I plan to maintain the code in the submodules referenced from this repository.






NOTES: 
This repository isn't endorsed or sanctioned by anyone. I am simply sharing my personal experiments and theoretical exercises with others.

I'd be interested in seeing your templates. 