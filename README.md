# fixmyfonts
my variant of Luke Smith's font fix that I use to fix arch/artix fonts when they break

put this into ~/.config/fontconfig/fonts.conf (create if it doesn't exist) to set system-wide default fonts (shouldn't affect your tty)

on arch/artix, requires the packages fontconfig, ttf-linux-libertine, and ttf-hack. maybe some other packages but i think that's all of them.

does not use Inconsolata like Luke Smith's original fonts.conf because when i tried it with a fonts.conf like this one, it broke the fonts everywhere on my system. Hack has not given me any problems.
