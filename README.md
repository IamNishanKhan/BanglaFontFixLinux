# Bangla_Font_Fix_Linux
Font fix for browsers
Fix small Bangla font problems in Linux

This will fix small or unsupported Bangla font problems in Linux. This will make "Nirmala UI" the default Bangla font in Linux. Nirmala UI is a truetype font made by Microsoft. And It renders Bangla font beautifully. Nirmala UI is the default Bangla font in Windows 10.

Copy all Windows 10 fonts into the "/usr/share/fonts/win10-fonts" folder. Font Link: https://drive.google.com/file/d/1CW8p4fQnFpEckJybS67iLKD6YZtHZycr/view?usp=sharing

Put the "50-custom-bangla.conf" file into the ".config/fontconfig/conf.d/" directory. [create if the directory doesn't exist]
```wget https://github.com/N1sh4n/Bangla_Font_Fix_Linux/blob/main/50-custom-bangla.conf && mkdir -p ~/.config/fontconfig/conf.d && cp 50-custom-bangla.conf $_```
Extra steps for Firefox users:  
<br>
Go to: Preference -> Language & Appearance -> Fonts & Colors  
From Advanced -> Fonts for -> Select Bengali  
<br>

Set->  
Proportional: Serif, Size -> 16  
Serif: Nirmala UI,    
Sans-serif: Nirmala UI  
Monospace: Consolas, Size: 12  
Minimum font size: None  
Click Ok.  
  
Again Select Latin  
Set-> Proportional: Serif, Size -> 16  
Serif: Times New Roman,   
Sans-serif: Arial  
Monospace: Consolas, Size: 12  
Minimum font size: None  
Click Ok.  
  
Now Select the default font: Times New Roman.
