# config-backups
 backups for picom and i3. 

The "config" file (with no file extension) is the i3 config file, customized to the keybinds I like (resize enabled, auto-open firefox disabled, and picom custom config enabled along with a line to enable picom --experimental-backends -b on startup. This config file needs to be copied into the directory /home/derekg/.config/i3/

the picom.config file can just go in the home directory, /home/derekg/. This is one of the default locations for picom to check for a config file, it should find it there no problem. Picom needs to be restarted before it can take effect sometimes. This requires (for me and my technical ability) a full reboot. I disabled shadows and tweaked the opacity for active and inactive alacritty windows. Oh yeah, this is setup so alacritty is the default terminal.

BOTH THESE FILES ARE CONFIGURED FOR ALACRITTY TO BE THE DEFAULT TERMINAL, INSTALL ALACRITTY. 
