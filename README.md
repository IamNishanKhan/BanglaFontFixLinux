# Bangla_Font_Fix_Linux
Font fix for browsers
Fix small Bangla font problems in Linux

This will fix small or unsupported Bangla font problems in Linux. This will make "Nirmala UI" the default Bangla font in Linux. Nirmala UI is a truetype font made by Microsoft. And It renders Bangla font beautifully. Nirmala UI is the default Bangla font in Windows 10.

Copy all Windows 10 iso or system fonts into the "/usr/share/fonts/win10-fonts" folder. Take a look at here how to extract fonts from Windows: https://wiki.archlinux.org/index.php/Microsoft_fonts#Extracting_fonts_from_a_Windows_ISO
or download from this repo https://github.com/tazihad/win10-fonts

Put the "50-custom-bangla.conf" file into the ".config/fontconfig/conf.d/" directory. [create if the directory doesn't exist]

wget https://raw.githubusercontent.com/tazihad/bangla-fonts-fix-linux/main/50-custom-bangla.conf && mkdir -p ~/.config/fontconfig/conf.d && cp 50-custom-bangla.conf $_
