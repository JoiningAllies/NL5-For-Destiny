
# This was uploaded as a response to the 4/17/24 ban wave that hit countless people for using different tweaks, base limiter versions, and overlays.
I plan on making changes here and there to make it more safe with less detection vectors but there is only so much I can do until I finish my personalized Limiter that is in the works.
I will be uploading that free of charge when it is completed but there are no planned dates on when it will be.

As for safety versus other free uploads the two main ones are made by Joyeuse and Bosslawl. Both of which don't have very many strings changes. Mine may not be more secure, but if battleye ever decides to start detecting other random strings within the program that say "*Netlimiter*" or things of the sort then every limiter aside mine would get cooked. I have plans to add more and more features as they are requested but have no timeframe as to when they will be added. Cry about it I guess. But I won't be badgered to add a feature. If I am then the feature will never be added. 

## [Virus Total](https://www.virustotal.com/gui/file/79125cfd0e3bd4e5880dc16cfd144edd7c0215eb3b98563edcb7eff4400f2acf?nocache=1)

# How To Setup Raw Limiter ![rikka](https://i.ibb.co/JkHBp0y/yiy587u6-r.png)

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
- When creating a filter the editor now says "Application is - Destiny" followed by "Remote Port In Range"
- Removed the word *"List"* from rule list, filter list, etc.
- Added under the *"Help"* tab links to this page, netlimiter bible, and my discord account
- Made a special change within the **Theme** tab that you will have to find yourself

![remoteportinrange](https://i.ibb.co/KFmCKTs/kjhdsfg-1.png)


# Security Changes?

- Changed 696 instances of "Netlimiter", "Locktime Software", "nlsvc", "NL4", and "NL5" (*Keep in mind there are still instances of these within the program itself that if tampered with cause the program to not work*)
- Removed "Netlimiter.com" hooks to reject updates (*Updates will not longer open a tab causing a "Plum" unless certain tabs are pressed manually*)
- Changed assmebly to no longer include "Netlimiter" and names associated with it.

# Support Me <3

- If you want to support me in my work please feel free to attack me in Discord <3 My profile is linked within the program under the help tab!
- You can also ask in the Netlimiter Bible discord for me.
