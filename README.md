---
{}
---

# Summary
- [WYSIWYG](https://github.com/Mara-Li/Obsidian-Snippet-collection#wysiwyg-and-pseudo-wysiwyg)
- [Colored Folder](https://github.com/Mara-Li/Obsidian-Snippet-collection#colored-folder)
- [Folder Icons](https://github.com/Mara-Li/Obsidian-Snippet-collection#folder-icons)

# WYSIWYG and Pseudo WYSIWYG
Note : Some screenshoot are outdated, the code is always updated, I don't have the time to take screen and update it each day.

This is the maximum I can do with only CSS. 
The only veritable problem is with the Active-Line : Code mirror can’t have, at the same time, active line + Selection, so it will remove it and the selection will “twinkle”. 
In the same way, I can’t render the table as WYSIWYG but the plugin "advanced table" can help a lot to create table.

I use, here :
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) ⚠️ This plugin is required to get the mobile mode.
- [Outliner](https://github.com/vslinko/obsidian-outliner)
  
Style Settings option : (⭐️ option exist only on Semi WYSIWYG, 🌔 only for WYSIWYG)
  - Display Image link ⭐️
  - Mobile support 🌔
    - Markdown clutter opacity 🌔
    - Header display 🌔
    - Icon URL (on mobile) 🌔
  - Highlight Background
  - Header options 
    - Clutter ⭐️
    - Display the header clutter with "H1", "H2" etc... ⭐️
    - Font size ⭐️
    - Underline for H1
  - Clutter Options  
    - Opacity ⭐️
    - Active line opacity ⭐️
    - Font size 
  - Link option : 
    - Color
    - Remplace link by an icon
  - Blockquote : Display them and color 
  - Tags : Color, padding  
  - Task: 
    - Color, 
    - Margin PC,
    - Margin Mobile 🌔
    - Top (only for PC) 

## Semi WYSIWY note
The main difference between the semi and the full is that :
- Semi doesn't work on mobile
- All markdown clutter are displayed, I use size and opacity to give them a little space. Active line change only the color. 

This Semi WYSIWYG mode is more like the mobile mode on the full snippet. It prevent the "cursor jump" with the text selection. 

## Wysiwyg code mirror companion
It's a little snippet that must be used with the plugin [Code Mirror Options](https://github.com/nothingislost/obsidian-codemirror-options). It works only for PC.


## Information about mobile support
On mobile, the code mirror version used is **Code Mirror 6**, not **Code Mirror 5**. So, activeline doesn’t work. I use another “tricks” to create a WYSIWYG view. For example :
- You will see the formatting with a little size and opacity.
- Link will be replaced by a icon, but you can always go to them, and you can saw them with backspace.
- Task will be replaced by symbol. To add the x, just go in and add it, you will see the update. Yeah, it's a little strange and tricky. I advice you to use the preview to check your task.

Also, I test only on IOS / IpadOS. If you saw any problem on android, please, provide an issue and a solution. I can't check for android for that.


## Installation

It's more an advice than an obligation, but I update a lot this, so unless you want to download / check the page each minute...

1. Clone this repository in your `.obsidian/snippet`
2. Move `.git`, and `wysiwyg.css` snippet in your folder. 
3. Delete the `Obsidian-WYSIWYG` folder.

Now, each time there is a update, you can just do `git pull` in a terminal/cmd. You can create a task for that, because sometimes I will not warn user each time !

Note : With this setup, you **will not be able** to edit the file, because each update erase your personal edit. Create another snippet OR create a pull request/issue with your personal edit. 

## Screenshot and preview.
### PC
#### Full WYSIWYG
![image](https://user-images.githubusercontent.com/30244939/129886682-b76bc8a2-cbe5-4a8e-83ec-e6ab4cea0e76.png)
![image](https://user-images.githubusercontent.com/30244939/129886939-9ef652ee-b905-4bbb-b89b-a15eddfbb064.png)
![image](https://user-images.githubusercontent.com/30244939/129886995-d8f8fcfa-49d7-41a5-b884-080c4a54fa9f.png)
![image](https://user-images.githubusercontent.com/30244939/129887413-d083af11-3987-4ea9-a7ff-e462055e6df8.png)

#### Semi-Wysiwyg
![image](https://user-images.githubusercontent.com/30244939/129887499-94c7800c-3eb8-4ae8-8312-c564a81775f4.png)
![image](https://user-images.githubusercontent.com/30244939/129887536-ec5b0d51-a30e-4d89-b2a7-6e908c25f886.png)
![image](https://user-images.githubusercontent.com/30244939/129887585-21c178bd-f9d8-4bf1-a8be-c5336b483435.png)
![image](https://user-images.githubusercontent.com/30244939/129887665-02d8b446-243d-4b41-a5e3-64fdf113c713.png)

##### Code Mirror Options Companions

#### Source
- [Clutter Free](https://forum.obsidian.md/t/clutter-free-edit-mode/6791)
- [Pseudo Like WYSIWYG](https://forum.obsidian.md/t/psuedo-live-markdown-with-css/6257/3)
- [Base](https://github.com/Dmitriy-Shulha/obsidian-css-snippets/blob/develop/Snippets/WYSIWYG.md)

---
# Colored Folder
You can change the color with style settings.

![image](https://user-images.githubusercontent.com/30244939/129755273-16d8c8cb-957a-42f1-8c11-dd0cc832e147.png)

---
# Folder Icons
⚠️ **You need to download TOO the [icon-font.css](https://raw.githubusercontent.com/Mara-Li/Obsidian-Snippet-collection/main/folders.icon.font.css) to use this snippet**

For font settings, you need to download 
- You can change the icon and their font in Style Settings : Note, you need to download [this snippet](https://github.com/Mara-Li/Obsidian-Snippet-collection/blob/main/folders.icon.font-settings.css) (there are too much option to have it on one snippet)
- You can change the color in style settings
- Adjusted for 00 → 100 → ZZ (ten to ten) folder and some nested folder 

![image](https://user-images.githubusercontent.com/30244939/129755594-d5bb6171-6f77-483d-8957-0d2dd460511a.png)

Some folder are adjusted for **my** icons and **my** folder, so you maybe need :
- Delete some part of the codes because of my settings
- Change `top` and `vertical-align` value. I don't add it to Style Settings because it because I need to create **for each folder and icons** a variable and it will kill Style Settings and my obsidian. Don't worry, it takes like ~2s to edit that with search.
- There is a snippet example to how to edit the snippet for mobile/PC : [Adjusting Snippet](https://github.com/Mara-Li/Obsidian-Snippet-collection/blob/main/folders.icon.adjust.css)
- Add your folder. You can just copy paste and add your icons, font and name. 

There is some adaptation too for mobile where you can add your settings. 

⚠️ For IOS : If you don't have Textastic (can open `.obsidian` folder) you need to use shortcuts and toolbox pro to open hidden folder. 
You can also use [ashell](https://holzschu.github.io/a-Shell_iOS/) (Free) to open `.obsidian` and file !