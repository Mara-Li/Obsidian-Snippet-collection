# WYSIWYG and Pseudo WYSIWYG
Note : Some screenshoot are outdated, the code is always updated, I don't have the time to take screen and update it each day.

This is the maximum I can do with only CSS. 
The only veritable problem is with the Active-Line : Code mirror can’t have, at the same time, active line + Selection, so it will remove it and the selection will “twinkle”. 
In the same way, I can’t render the table as WYSIWYG but the plugin "advanced table" can help a lot to create table.

I use, here :
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) ⚠️ This plugin is required to get the mobile mode.
- [Outliner](https://github.com/vslinko/obsidian-outliner)
- [Yin and Yang theme](https://github.com/chetachiezikeuzor/Yin-and-Yang-Theme/)  
  Note that my WYSIWYG will edit some WYSIWYG item of the option in this theme. 
  
Style Settings option : 
- Quote block color
- Mobile support. 


---

### Information about mobile support
On mobile, the code mirror version used is **Code Mirror 6**, not **Code Mirror 5**. So, activeline doesn’t work. I use another “tricks” to create a WYSIWYG view. For example :
- You will see the formatting with a little size and opacity.
- Link will be replaced by a icon, but you can always go to them, and you can saw them with backspace.
- Task will be replaced by symbol. To add the x, just go in and add it, you will see the update. Yeah, it's a little strange and tricky. I advice you to use the preview to check your task.

Also, I test only on IOS / IpadOS. If you saw any problem on android, please, provide an issue and a solution. I can't check for android for that.

---
### Installation

It's more an advice than an obligation, but I update a lot this, so unless you want to download / check the page each minute...

1. Clone this repository in your `.obsidian/snippet`
2. Move `.git`, and `wysiwyg.css` snippet in your folder. 
3. Delete the `Obsidian-WYSIWYG` folder.

Now, each time there is a update, you can just do `git pull` in a terminal/cmd. You can create a task for that, because sometimes I will not warn user each time !

Note : With this setup, you **will not be able** to edit the file, because each update erase your personal edit. Create another snippet OR create a pull request/issue with your personal edit. 

---

## Screenshot and preview.

**Font used :**
- Preview : Tenorite
- Editor : IA Writer Quattro S
- Title (preview & editor) : Seaford
- Mobile : Tenorite

### PC

![image](https://user-images.githubusercontent.com/30244939/122135791-78370580-ce41-11eb-9d6f-386960e015fa.png)
![image](https://user-images.githubusercontent.com/30244939/122135835-97359780-ce41-11eb-81da-b5557391f7e4.png)
![image](https://user-images.githubusercontent.com/30244939/122137099-26dc4580-ce44-11eb-8b3a-a19e3f0ab9ed.png)
![image](https://user-images.githubusercontent.com/30244939/122203069-f5906380-ce9d-11eb-9554-330a4e23941f.png)

https://www.youtube.com/watch?v=lcAEHRMZS9o

### Mobile

![IMG_0329](https://user-images.githubusercontent.com/30244939/122211028-9256ff00-cea6-11eb-8d6f-dccb13dc3766.PNG)
![IMG_0330](https://user-images.githubusercontent.com/30244939/122211037-95ea8600-cea6-11eb-87ad-f652599d56b7.PNG)
![IMG_0332](https://user-images.githubusercontent.com/30244939/122211049-997e0d00-cea6-11eb-8202-4cf5f7db0053.PNG)
![IMG_0333](https://user-images.githubusercontent.com/30244939/122211063-9d119400-cea6-11eb-9893-0c60c63d0456.PNG)
![IMG_0336](https://user-images.githubusercontent.com/30244939/122211085-a13db180-cea6-11eb-80c0-ca29643faaf8.PNG)

https://youtu.be/2U9TEmWFTTw

## SEMI-WYSWYG [PC ONLY]

⚠️ It's ONLY for PC. If you need a wysiwyg for mobile, I beg you to use the first version of the snippet. 
- I use opacity/transparency instead of display none.  
- I don't use at all codemirror line and active line, UNLESS for the `hr` and checkbox.
- Templater update is also in, in case of any problem.
- Option to display or not the clutter for header. 
- You can display link with arrow as mobile version
- The opacity up when active line, but you can change this behaviour with style settings. You can also change the opacity mesure.

![image](https://user-images.githubusercontent.com/30244939/124671276-895dba00-deb5-11eb-996d-1902f1a6e3fe.png)
![image](https://user-images.githubusercontent.com/30244939/124671258-8367d900-deb5-11eb-8b03-ca19891dec0d.png)
![image](https://user-images.githubusercontent.com/30244939/124672385-3c7ae300-deb7-11eb-8423-a4ef7331f56a.png)
![image](https://user-images.githubusercontent.com/30244939/124672392-400e6a00-deb7-11eb-8c04-5202430e3771.png)
![image](https://user-images.githubusercontent.com/30244939/124673303-e7d86780-deb8-11eb-9cd2-553bbe9e71b8.png)


----
#### Source
- [Clutter Free](https://forum.obsidian.md/t/clutter-free-edit-mode/6791)
- [Pseudo Like WYSIWYG](https://forum.obsidian.md/t/psuedo-live-markdown-with-css/6257/3)
- [Base](https://github.com/Dmitriy-Shulha/obsidian-css-snippets/blob/develop/Snippets/WYSIWYG.md)
