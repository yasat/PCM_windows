Run pcm.exe from cmd with admin privileges.
Note: add to PATH, to run from python subprocess module

-csv : to save output (pref. csv)
-nc : no core info
-ns : no socket info

To create csv log for every 10 milliseconds:
pcm.exe 0.1 -csv=log.csv