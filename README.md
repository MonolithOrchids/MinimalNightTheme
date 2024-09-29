# Fork of the [**DiscordNight**](https://github.com/KillYoy/DiscordNight) made by KillYoy.
## Some visual changes were made as an attempt to restore visuals broken with newer updates.

![](https://i.imgur.com/Ov1iSAp.png)

Requires the [**Discord**](https://discordapp.com/) desktop app with [**BetterDiscord**](https://betterdiscord.app/) or [**Vencord**](https://vencord.dev) installed (Or any other Discord client mod that supports themes).

### [**BetterDiscord**](https://betterdiscord.app/):  
- Download [**MinimalNight.theme.css**](https://github.com/MonolithOrchids/MinimalNightTheme/blob/master/MinimalNight.theme.css) and navigate to **Settings > Themes** and click **Open Themes Folder** or place the file in **%appdata%/BetterDiscord/themes** and then enable **MinimalNight**.  
If the theme does not show up refresh Discord using **CTRL+R** or restart Discord.

### [**Vencord**](https://vencord.dev):  
- ***Method 1***: 
	- Download [**MinimalNight.theme.css**](https://github.com/MonolithOrchids/MinimalNightTheme/blob/master/MinimalNight.theme.css) and navigate to **Settings > Themes** and click **Open Themes Folder** or place the file in **%appdata%/Vencord/themes** and then enable **MinimalNight**.    
- ***Method 2***: 
	- Navigate to **Settings > Themes** and go to **Online Themes** tab and in the input field paste in this URL:  
```https://raw.githubusercontent.com/MonolithOrchids/MinimalNightTheme/master/MinimalNight.theme.css```

### Important info

- **Dark Theme** needs to be enabled in **Settings > Appearance > Theme** and select **Dark**.

# Preview

![Main window](https://i.imgur.com/wzOZXtE.png)
# 
![Settings comparison](https://i.imgur.com/DDSlClq.png)

# Customizing the theme

MinimalNight has certain unique variables that can easily be modified to change the visibility and width of certain elements. The code can either be added to the **MinimalNight.theme.css** or the **Custom CSS** menu in Discord settings:

```css
:root {
    --Channel-Invite-Edit-Buttons: none;                 /* flex = ON, none = OFF */
    --Channel-Category-Invite-Button: flex;              /* flex = ON, none = OFF */
    --Channel-List-Active-Threads: flex;                 /* flex = ON, none = OFF */
    --Channel-List-Upcoming-Events: flex;                /* flex = ON, none = OFF */
    --Channel-List-Boost-Goal: block;                    /* block = ON, none = OFF */
    --Channel-List-Width: 200px;                         /* 200px, Discord default = 240px */
	
    --User-List-Width: 200px;                            /* 200px, Discord default = 240px */
    --User-Popout-Width: 240px;                          /* 240px, Discord default = 300px */
    --User-Status-Popout-Width: var(--User-Popout-Width);/* 240px, Discord default = 300px */
	
    --Search-List-Width: 488px;                          /* 488px, Discord default = 418px */
    --Inbox-List-Width: 522px;                           /* 522px, Discord default = 480px */
	
    --Emoji-Menu-Height: 618px;                          /* 618px or 498px, Discord default = 444px */
	
    --Chatbox-Gift-Button: none;                         /* flex = ON, none = OFF */
    --Chatbox-GIF-Button: none;                          /* flex = ON, none = OFF */
    --Chatbox-Stickers-Button: none;                     /* flex = ON, none = OFF */
	
    --Chat-Emoji-Size: 1.75rem;                          /* 1.75rem, Discord default = 1.375rem */
    --Chat-Emoji-Large-Size: 2rem;                       /* 2rem, Discord default = 3rem */
    --Chat-Sticker-Size: 5rem;                           /* 5rem, Discord default = 10rem */
    --Chat-Super-Reaction-Button: none;                  /* flex = ON, none = OFF */
    --Chat-Wave-To-New-User-Button: flex;                /* flex = ON, none = OFF */
    --Chat-Wave-To-New-DM-Button: flex;                  /* flex = ON, none = OFF */
	
    --Text-Channels-Capital-Letter: capitalize;          /* capitalize, none */
	
    --Voice-Noise-Suppression: none;                     /* flex = ON, none = OFF */
    --Start-Activities-Button: flex;                     /* flex = ON, none = OFF */
	
    --Embed-Remove-Button: flex;                         /* flex = ON, none = OFF */
	
    --Context-Menu-Emoji-Toolbar: none;                  /* flex = ON, none = OFF */
	
    --Home-Nitro-Button: none;                           /* flex = ON, none = OFF */
    --Home-Store-Button: none;                           /* flex = ON, none = OFF */
    --Home-Direct-Messages-Header: flex;                 /* flex = ON, none = OFF */
    --Home-Close-DM-Button: block;                       /* block = ON, none = OFF */
    --Friends-List-Searchbar: none;                      /* flex = ON, none = OFF */
	
    --Titlebar-Help-Icon: none;                          /* flex = ON, none = OFF */

    --Activity-Status: flex;                             /* flex = ON, none = OFF */

    --si-size: 24px;					/* Size for sidebar icons (Default: 24px) */
    --si-animations: true; 				/* [true/false] Adds sidebar animations (Default: true) */
	
    --Edit-Image-with-Apps: none;			/* flex = ON, none = OFF */

    --Reaction-Message-Hover: flex;			/* flex = ON, none = OFF */
}
```

## Want certain things to look like they normally do in Discord?
I have made some import addons which changes certain aspects of the theme.   
You can change the **Server list message notice** and **Chat file attachment button** back to their original appearance by adding either of these two lines of code to your **MinimalNight.theme.css**

```css 
@import url("https://raw.githubusercontent.com/MonolithOrchids/MinimalNightTheme/master/Addons/Vanilla_ServerList_Message_Notice.theme.css"); 
```   
```css 
@import url("https://raw.githubusercontent.com/MonolithOrchids/MinimalNightTheme/master/Addons/Vanilla_Attachment_Button.theme.css"); 
```

## Installing DiscordNight to your internet browser

- By using a stylesheet addon like Stylus, you can create a style for **discordapp.com** and paste in the code from **MinimalNight.css** (Not everything will work correctly like scrollbars and external images)
