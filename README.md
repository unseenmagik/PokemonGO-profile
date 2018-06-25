Pokemon GO Profile Parsing
==========================
Python script to parse Player Level out of Profile Screenshot and verify the Username in the Screenshot with a given Username.

Needs Python3.

Module Usage
-----------
```
import poke_profile
result = poke_profile.getLevel(fullimagepath, username)
print(result[0])                          # the found level or None
print(result[1])                          # booleon; true, if the given username was found
```
Standalone Usage
-----
```
usage: poke_profile.py [-h] -i IMAGE -u USERNAME [-p PLOT]

optional arguments:
  -h, --help            show this help message and exit
  -i IMAGE, --image IMAGE
                        path to input image to be OCR'd
  -u USERNAME, --username USERNAME
                        username to search in OCR output
  -p PLOT, --plot PLOT  true, to display plot, false else
```
