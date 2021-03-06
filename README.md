# User-CSS-For-Firefox-And-Thunderbird
User CSS Contributions For CustomizeMyBird and Custom CSS For FX

This repository is for user submitted CSS customizations for:
1.  The very excellent Firefox and Thunderbird add-ons by Aris-t2 at https://github.com/Aris-t2 ; and
2.  Other useful CSS contributions for Firefox and Thunderbird.

If you like Windows 7 or XP and you also like the Windows Classic XP/Win2000 look on Windows 7, then you may really like what the files here can do for you.

Note:  I prefer the older look of Windows XP/2000 over the Windows 7 Aero interface.  Therefore, I use the Classic Windows Theme on Win 7 as my starting point.  Then I add the "Classic Start Menu" available from http://www.classicshell.net/ .  Then for Firefox I use the "themefirefoxblue" theme (https://addons.mozilla.org/en-US/firefox/addon/themefirefoxblue/).  For Thunderbird I use the Blue-FK theme by Fantastic-King (https://addons.thunderbird.net/en-US/thunderbird/addon/blue-fk/?src=userprofile).  This theme is a dark theme for the toolbar, bookmarks toolbar, and menu bar areas.  For Thunderbird on my Windows 7 setup, I use CustomizeMyBird add-on and I used to also use Theme and Font Size Changer add-on.  But I have now effectively incorporated Theme and Font Size changer into my own custom userChrome CSS, so no longer use Theme and Font Size Changer.  Plus my own custom UserChrome CSS is placed in the CustomizeMyBird user CSS window.

Various standard color choices from add-ons don't work as well as I would like (colorwise) with my Windows Classic Theme setup.  Also, I like rounded tabs and spacing that is a little bit different from what the add-ons usually provide.

Therefore, I've had to use userChrome CSS to modify some of the setup from Custom CSS For FX and CustomizeMyBird to get the look I find pleasing.

If you don't like the color choices in my CSS it can of course be easily modified if you know how to use CSS in a userChrome file.

Also, remember I am no programmer so let me apologize in advance if my CSS looks funny or something.

If you want to further duplicate my color setup on Windows 7 then first select the Classic Windows Theme.  After that download the JYLD_Color_Choices.zip file to your computer and then double click the reg files it contains to add it to your registry.  You should save a copy of your current theme before doing this so you can go back to your original color choices.  Also note that my color choices work on Windows 7 and XP.  On Windows 7 you must be using the Windows Classic Theme for the color choices in the JYLD_Color_Choices.zip file to have any effect.  After adding the color choices reg file settings to your registry you will have to reboot your computer for the changes to take effect.  

NOTE:  I have no idea how the color choices reg files would affect Windows 8 to 10, if at all.  I don't even know if the Windows Classic Theme is available on Windows 8 to 10.

Based on how my CustomizeMyBird/Thunderbird CSS tweaks work on my wife's Windows 7 aero interface computer, I can say that CustomizeMyBird, CSSFx For Firefox, and my tweaks to both of these all work very well with the aero interface.  I would not use my reg files to adjust the colors if you use the Windows Aero/Glass interface.  Instead I recommend you use the default color setup and first try one of the aero blue themes.  Also, in my opinion Thunderbird looks much better with either the classic or aero/glass interfaces if you have the title bar turned on.  Its off by default in Thunderbird.  

To turn on the title bar in Firefox or Thunderbird set this value in about:config browser.tabs.drawInTitlebar = false

You can contact JYLD at g a r y AT g a r y b r i t t DOT c o m (delete spaces and make substitutions).

UPDATE:

If you implement the latest version of my CSS for CMB or in a userChrome.css file and if you use a Thunderbird theme like I am currently using Blue-FK by Fantastic King https://addons.thunderbird.net/en-US/thunderbird/addon/blue-fk/?src=userprofile then you don't need to have Theme & Font Size Changer installed at all.

UPDATE 2:

If you use my css with thunderbird 68+ remember to set this:

Settings/Options > Advanced > General > Config Editor...
toolkit.legacyUserProfileCustomizations.stylesheets to true

Most of my userChrome.css will work stand alone without CustomizeMyBird and most of it should work with TB 68+ and 78+.
