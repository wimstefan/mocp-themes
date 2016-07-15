##############################################################################
#
# Theme in black|red|white by Stefan Wimmer <wimstefan@gmail.com>
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

background           = default default
frame                = red     default bold
window_title         = default default reverse
directory            = default default dim
selected_directory   = default default dim,reverse
playlist             = default default
selected_playlist    = default default reverse
file                 = default default
selected_file        = default default reverse
marked_file          = default default bold
marked_selected_file = default default bold,reverse
info                 = default default
selected_info        = default default bold
marked_info          = red     default bold
marked_selected_info = red     default bold,reverse
status               = default default
title                = default default bold,dim
state                = default default
current_time         = default default bold
time_left            = default default bold
total_time           = default default bold
time_total_frames    = default default
sound_parameters     = default default bold
legend               = default default
disabled             = default default
enabled              = red     default bold
empty_mixer_bar      = default default
filled_mixer_bar     = default default reverse
empty_time_bar       = default default
filled_time_bar      = default default dim,reverse
entry                = default default
entry_title          = default default
error                = red     default
message              = default default standout,reverse
plist_time           = default default bold
