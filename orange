##############################################################################
#
# Theme in yellow|red by Stefan Wimmer <wimstefan@gmail.com>
#
##############################################################################
# The format of this file is:
# Lines beginning with # are comments.
# Blank lines are ignored.
# Every other line is expected to be in format:
#
# ELEMENT = FOREGROUND_COLOR BACKGROUND_COLOR [ATTRIBUTE[,ATTRIBUTE,..]]
#
# or
#
# colordef COLOR = RED GREEN BLUE
#
# Where names are case insensitive.
#
# ELEMENT is an element of MOC interface. This can be:
# background           - default background for regions when nothing is displayed
# frame                - frames for windows
# window_title         - the title of the window (eg name of the current
#                        directory)
# directory            - a directory in the menu
# selected_directory   - a directory that is selected using arrows
# playlist             - playlist file
# selected_playlist    - see selected directory
# file                 - an ordinary file in the menu (mp3, ogg, ...)
# selected_file        - see selected directory
# marked_file          - a file that is currently being played
# marked_selected_file - a file that is currently being played and is also
#                        selected using arrows
# info                 - information shown at the right side of files
# selected_info        - see selected directory
# marked_info          - a file (its time) that is currently being played
# marked_selected_info - a file (its time) that is currently being played
#                       and is also selected using arrows
# status               - the status line with a message
# title                - the title of the file that is currently being played
# state                - the state: play, stop, or paused (>, [], ||)
# current_time         - current time of playing
# time_left            - the time left to the end of playing the current file
# total_time           - the length of the currently played file
# time_total_frames    - the brackets outside the total time of a file ([10:13])
# sound_parameters     - the frequency and bitrate numbers
# legend               - "KHz" and "Kbps"
# disabled             - disabled element ([STEREO])
# enabled              - enabled element
# empty_mixer_bar      - "empty" part of the volume bar
# filled_mixer_bar     - "filled" part of the volume bar
# empty_time_bar       - "empty" part of the time bar
# filled_time_bar      - "filled" part of the time bar
# entry                - place wher user can type a search query or a file name
# entry_title          - the title of an entry
# error                - error message
# message              - information message
# plist_time           - total time of displayed items
#
# FOREGOUND_COLOR and BACKGROUND_COLOR can have one of the following values:
# black, red, green, yellow, blue, magenta, cyan, white, default (can be
# transparent), grey (not standard, but works)
#
# Optional ATTRIBUTE parameters can be (from ncurses manual):
# normal      - default (no highlight)
# standout    - best highlighting mode of the terminal
# underline   - underlining
# reverse     - reverse video
# blink       - blinking
# dim         - half bright
# bold        - extra bright or bold
# protect     - protected mode
#
# You can specify a list of attributes separated by commas: attr1,attr2,attr3.
# Don't use spaces anywhere in such a list.
#
# With colordef you can change the definition of a color. It works only if
# your terminal supports it, if not those lines will be silently ignored.
# COLOR must be a valid color name and the RED GREEN and BLUE are numbers
# from 0 to 1000. Example:
#
# colordef red = 1000 0 0
#
# HINT: you have only 8 colors, but combined with attributes bold and/or
# reversed you actually get more colors.
#
# If you don't specify some elements, the default values will be used.
#
##############################################################################

background           = red     default
frame                = red     default
window_title         = red     default
directory            = yellow  default
selected_directory   = red     default
playlist             = yellow  default
selected_playlist    = yellow  default
file                 = yellow  default
selected_file        = black   yellow
marked_file          = red     default
marked_selected_file = red     yellow
info                 = yellow  default
selected_info        = yellow  default bold
marked_info          = yellow  default bold,reverse
marked_selected_info = red     default bold
status               = yellow  default
title                = yellow  default
state                = yellow  default
current_time         = yellow  default
time_left            = yellow  default
total_time           = yellow  default
time_total_frames    = yellow  default
sound_parameters     = yellow  default
legend               = yellow  default
disabled             = red     default dim
enabled              = yellow  default bold
empty_mixer_bar      = black   red
filled_mixer_bar     = black   yellow
empty_time_bar       = yellow  default
filled_time_bar      = default yellow
entry                = yellow  default
entry_title          = yellow  default
error                = cyan    default
message              = yellow  default
plist_time           = yellow  default
