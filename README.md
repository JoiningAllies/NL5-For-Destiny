
# This was uploaded as a response to the 4/17/24 ban wave that hit countless people for using different tweaks, base limiter versions, and overlays.
I plan on making changes here and there to make it more safe with less detection vectors but there is only so much I can do until I finish my personalized Limiter that is in the works.
I will be uploading that free of charge when it is completed but there are no planned dates on when it will be.

## [Virus Total](https://www.virustotal.com/gui/file/697d5496e9275525cc1df9bfde15b845fa62441d23995118cc69bf4b1ddcb0b0/detection) ![rikka](https://i.ibb.co/hKNYXBw/image-2024-05-08-095041621.png)

# How To Setup Raw Limiter

- Click on Code and Download ZIP from the dropdown menu
- Extract the files somewhere on your pc and remember where
- Install **netlimiter-5.1.4.0.exe** and finish installation
- Open Command Prompt as admin and type in **net stop nlsvc**
- Drag and drop each file inside of **Rikkas Files** into your C:\Program Files\Locktime Software\Netlimiter File or your installation path
- Reopen Command Prompt as admin and type in **net start nlsvc**
- Open **Rikka.exe**

# How To Setup Destiny 2 Limits

- Open **Filter List**
- Click **Add Filter**
- Filter name can be whatever you want it to be for your specific limit
- Click **Add**
- Choose function **Application Is** = Destiny2.exe
- Click **Add**
- Choose function **Remote Port In Range** = The port you are using for that specific limit
- Save
- Open **Rule List**
- Click **Add Limit**
- Select -> Filters -> The filter we just made
- Change **KB/s -> B/s**
- Change **5120 -> 1**
- Untick the **Enabled** box
- Press **OK**
- Right click on the rule and add a keybind if you wish

# Visual Changes

- Active/Disabled Limit is now RTA/API

![APIRTA](https://i.ibb.co/Lkqhhc8/image-2024-05-08-091349138.png)


- Help tab now displays my personal discord link
- Help tab now says "Don't Click Me" on the update tab
- Help tab now says "Who made This?" on the About and Registration tab
- About and Registration now says "Made By Rikka <3" at the top
- Rule list now says "Add Limit" at the bottom instead of "Add rule"
- When creating a filter the editor now says "Application is - Destiny" followed by "Remote Port In Range"

![remoteportinrange](https://i.ibb.co/KFmCKTs/kjhdsfg-1.png)


# Security Changes?

- Changed 612 instances of "Netlimiter", "Locktime Software", "nlsvc", "NL4", and "NL5" (*Keep in mind there are still instances of these within the program itself that if tampered with cause the program to not work*)
- Removed "Netlimiter.com" hooks to reject updates (*Updates will not longer open a tab causing a "Plum" unless certain tabs are pressed manually*)
