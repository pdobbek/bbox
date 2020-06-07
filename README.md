# bbox
Simple bash script to back up files either in the original file's directory or in the standard
Dropbox directory (~/Dropbox/). Meant to be provide a simple terminal backup service.

bbox was created partly to serve my own needs and also as an exercise. There are probably better ways
of doing what bbox is doing. If you spot some glaring errors, whether in design or code, please let
me know. I am a novice programmer and welcome any input.
- Patryk (pdobbek@gmail.com)


# todo:
# -Comment out code.
# -Add option for backing-up both locally and in Dropbox at the same time.
# -Add option for saving to a hidden backup folder when backing-up locally.
# -Change backup file name so they inlcude ~ as last char.
# -Add option for clearing backup files.
# -Add option for having only one backup file at a time (or no more than a set
# number).
# -Add better getopts. Currently can't have separate args (e.g. -r -d), they
# have to be typed together (e.g. -rd).
# -Drop to_dropbox and other Dropbox mentions and replace with custom bbox
# folder. Allow the user to specify their own destination folder.
