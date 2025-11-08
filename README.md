
![Modified Lucid PREVIEW](https://github.com/user-attachments/assets/34ca3d1a-20ab-4f71-9aa8-0a3d6cd28206)

![Modified StarryNight PREVIEW](https://github.com/user-attachments/assets/3c9c4c33-d704-45e3-803e-3aaff9734bf5)


# Enjoy a better Spotify with this Spicetify setup!!

**Simple installation guide included of course** 

---

# HOW TO IMPLEMENT MY SPICETIFY SETUP

---

## IMPORTANT NOTES

- Use all the commands listed in this guide in PowerShell (no admin needed)  

- All versions of StarryNight might have a bug, may want to wait until it is properly fixed  

- FYI the `zoomTheme.js` extension is just for the SpotifyDarkPurp Theme  

---

## HOW TO INSTALL SPICETIFY

- There are several ways to do it but I suggest using this  

- Open PowerShell (regularly without admin)  

- Run the following command:  
```
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/main/install.ps1 | iex
```

- Enter **y** when prompted and hit enter to install the marketplace too  

- Then run:  
```
spicetify backup apply
```
You can also check out their page [Spicetify Installation Guide + Info](https://spicetify.app/docs/advanced-usage/installation)

---

## HOW TO APPLY THEMES

- Move or copy the folders inside **My Modified Themes** into this location:  
```
C:\Users\%USERNAME%\AppData\Local\spicetify\Themes
```

- Then run:  
```
spicetify config current_theme <nameofthemefolder>  
spicetify apply
```

---

### FORCE APPLY A MODIFIED COLOR SCHEME *(Might need to do for StarryNight)*

```
spicetify config current_theme <nameofthemefolder>  
spicetify config color_scheme <nameofcolorschemefile>  
spicetify apply
```

---

## HOW TO INSTALL `waveform.js` *(CUSTOM LOCAL FILE EXTENSIONS)*

The `waveform.js` extension is a custom extension from GitHub  
There is another one like it in the Spicetify Marketplace but it doesn't work on all themes so I suggest using this one  

- Place the `spicetify-waveform` folder and the `waveform.js` file into this location:  
```
C:\Users\%USERNAME%\AppData\Roaming\spicetify\Extensions
```

- Then run:  
```
spicetify config extensions waveform.js
```

---

## HOW TO INSTALL `history-in-sidebar` *(CUSTOM LOCAL FILE APPS)*

- Place the `history-in-sidebar` folder into this location:  
```
C:\Users\%USERNAME%\AppData\Roaming\spicetify\CustomApps
```

- Then run:  
```
spicetify config custom_apps history-in-sidebar
```

---

## HOW TO APPLY MY SPICETIFY SETTINGS / SETUP

- Open Spotify  

- Click the shopping cart (Marketplace Icon)  

- Select the gear icon **Spicetify Settings**  

- Under **Backup/Restore**, press **Open > Import From File**  

- Select the `marketplace-settings-2025-10-13T06_40_03.630Z.json` provided in this package  

---

## IF USING THE LUCID THEME — HOW TO APPLY MY LUCID THEME SETTINGS

- Once you have Lucid Theme applied you will see a tiny gear icon at the top right of Spotify — select it  

- In the top Settings navigation categories, scroll all the way to the right and select **Advanced**, or scroll all the way to the bottom  

- Open the `My Lucid Theme Setup.json` with Notepad  

- Press `Ctrl + A` to select all the contents and copy it  

- Paste them into the **Import Configuration** section of Lucid’s Advanced Settings section  

- You can customize the Lucid settings however you like from there :)  

---

## NOTES
- **Recommend to join the [Spicetify Discord](https://discord.com/invite/spicetify-842219447716151306)**

- You can customize the Spicetify addons however you like in the marketplace  

- There is also a `Spicetify Commands.txt` included in this pack if you ever need  

- This setup is just my personal favourite after having gone through everything like 20 times lol — enjoy  
\- **landn.thrn**

---

# CREDITS

### [Spicetify](https://spicetify.app)  

### [Lucid Theme](https://projects.sanooj.uk/spicetify/lucid)  

### [StarryNight Theme](https://github.com/spicetify/spicetify-themes/tree/master/StarryNight)  

### [Waveform](https://github.com/SPOTLAB-Live/Spicetify-waveform)  

### [History in Sidebar](https://github.com/Bergbok/Spicetify-Creations/blob/main/CustomApps/history-in-sidebar/README.md)   

---

## Found this useful?<img src="https://media.tenor.com/23NitOvEEkMAAAAj/optical-illusion-rotating-head.gif" width="30"><br>

[![Follow Me <3](https://img.shields.io/badge/Follow%20Me%20%3C3-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/landnthrn)   
[![Find More of my Creations on GitHub](https://img.shields.io/badge/Find%20More%20of%20my%20Creations%20on%20GitHub-311A82?style=for-the-badge&logo=github&logoColor=white)](https://github.com/landnthrn?tab=repositories)  
[![Gists: landnthrn](https://img.shields.io/badge/Gists-311A82?style=for-the-badge&logo=github&logoColor=white)](https://gist.github.com/landnthrn)  
[![Discord: landn.thrn](https://img.shields.io/badge/Discord-311A82?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/831735011588964392)  
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-311A82?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://buymeacoffee.com/landn.thrn/extras)  
[![PayPal](https://img.shields.io/badge/PayPal-311A82?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=K4PLHFVBH7X8C)

---
