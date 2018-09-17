# Doji's CSGO Configs

## About

One of the things I like most about CS:GO is the abilities given to users to cutomise their experience. I have a lot of fun finding good or silly binds and aliases that make the experience more enjoyable.
This config is what I ended up with after many hours of messing around, watching youtube videos, and browsing reddit.

!!!! BE SURE TO CHANGE THE VALUES DESCRIBED IN THE "Usage" SECTION !!!!

## Contents

The configuration files are divided into different parts to provide for an easier overview.
This is done mostly because I like to keep a clean ship, and because it makes editing easier.

My config contains the following

* autoexec.cfg : main runner of the configurations
* 01_alias.cfg : A whole bunch of aliases that can be bounds to any key you want
* 02_viewmodel.cfg: Viewmodel stuff
* 03_mouse.cfg: Mouse configuration and sensitivity.
* 04_network.cfg: Network configuration (rates/interp).
* 05_*: Crosshairs. These are referenced in 01_alias.cfg and can be quick switched by typing a command in console.
* 06_solo_practice.cfg : Nade and offline server practice script. Enables cheats and rebinds capslock to noclip.
* 07_useless_fps_tweeks.cfg: FPS boost stuff. This should not give you a performance hit. If it does, remove the script from the autoexec.
* 08_sound.cfg: My sound settings, based on what reddit told me. These settings are for 5:4 res.
* 09_keybinds_qwerty.cfg: My keybinds.
* 09_keybinds_qwerty_guest.cfg: Less obscure keybinds for when a guest is playing on my pc.
* 10_trashtalk.cfg: For fun script that loops through a whole bunch of silly insults. Don't take this too seriously, it was mostly made to have fun scripting.
* 11_null_cancel.cfg: Found this on a config scripting site. 
	* It is supposed to help with movement canceling. 
	* CURRENTLY NOT USED, but left in for reference.


## Usage

Paste the files into 'C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg' (or whatever folder/drive you installed steam on)

### CHANGE THESE

* 09_keybinds_qwerty.cfg: Change these to your liking.
* 04_network.cfg: Change these settings based on your internet connection
* 08_sound.cfg: 
	* Change the snd_mixahead if experiencing frame drops due to sound (higher == less CPU, slower sound. lower == more CPU, faster sound)
	* Change the 'volumes' to your liking
	* Change snd_front_headphone_position to match your resolution
* 01_alias.cfg:
	* Change the 'xhair_default' alias, and make it point to the crosshair you'd like to use. This alias is used to reset the crosshair after using the nade xhair.
	
	
### Console commands

Some aliases are not bound to keys and are intended to be used from the console.
Here is a list of commands that you can use:

* xhair_*NAMEGOESHERE* : Change your crosshair to one of those I have preconfigured.
* swagyolo: trolly visual mode. Your crosshair and HUD wil change color when shooting.
* ae: rerun the autoexec. Use this when changing binds (or other config) on the fly, so you don't have to restart CS:GO all the time.
* damage_on/damage_off: Toggle displaying of damage on the top of the screen. These commands exist because the console will be full of debug info when activated.
* bromode: execute the "09_keybinds_qwerty_guest.cfg" script, for when someone else wants to play on your pc.
* nadeprac: Start a private server (with bots) and run this command. It will execute the "06_solo_practice.cfg" script

# Crosshair overview

## 05_crosshair

A basic, thin, green crosshair.

## 05_01_spray_crosshair

Crosshair for practicing spray heights.
This is a dynamic crosshair that will indicate the spray height of the ak and the m4.
Aim with the outer most line for ak, and the inner one for m4.
These are customized for my resolution, so be sure to change some values if you want to use it.

## 05_02_crosshair_dot_spraying

Dynamic crosshair that will give you a dot when spraying.

## 05_02_swagmode

Silly crosshair used in the "yoloswag" alias.

## 05_023_crosshair_fat

Big fat green crosshair for when your eyes are tired.

## 05_024_crosshair_pink

Static wide, pink crosshair.

## 05_024_crosshair_pink_thin

A think, pink crosshair.

## 05_050_crosshair_t_abe

Static and fat T-shape crosshair.
I made it for a friend, called Abe.
This crosshair has a pretty low opacity, so it doesn't limit your view too much.

## 05_69_crosshair_white_dyna_dot

A custom, withe mix static/dynamic crosshair.
The outer part of the crosshair is static.
Inside is a dot that is made from the dynamic part.
If you run or shoot, the dot expands.
This crosshair is visible when using the knife.
If you are having trouble with standing still and shooting, I would recommend this crosshair.

# Bugs or suggestions

Feel free to leave me a message if you notice any bugs, or have any suggestions.
Happy fragging!


