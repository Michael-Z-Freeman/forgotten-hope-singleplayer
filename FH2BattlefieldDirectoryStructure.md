

# Introduction #

It's not always obvious where to find the places that FH2 functionality is implemented in various Battlefield 2 archives, ".con" files and python files. So this will be a map showing where to look.

# FH2 Structure Map #

  * ai\
    1. _aibehaviours.ai_, key file
  * binaries\
  * fh2settings\
  * levels\fhmapname\
    1. server.zip
      * _init.con_, kits and more set here.
  * localization\
  * menu\
  * movies\
  * python\
    1. game
  * settings\
  * clientarchives.con
  * gamelogicinit.con
  * init.con
  * serverarchives.con
  * mod.desc
  * fh2.ico
  * mod.png
  * mod\_icon.png
  * changelog.txt
  * common\_client.zip
  * common\_server.zip
  * fonts\_client.zip
  * menu\_client.zip
  * menu\_server.zip
  * objects\_client.zip
  * objects\_server.zip
    1. Kits
      * Class kit setup
    1. Kits/ai
      * _Objects.ai_, kit strengths.
  * objects\_statics\_client.zip
  * objects\_statics\_server.zip
  * objects\_vehicles\_client.zip
  * objects\_vehicles\_server.zip
  * objects\_weapons\_client.zip
  * objects\_weapons\_server.zip
    1. Weapons
      * armament
  * shaders\_client.zip

# Note to Editors #

Use [lists wiki markup](http://code.google.com/p/support/wiki/WikiSyntax#Lists). Link to sub sections on this page for descriptions or make a new page. For details .con and python files add lines numbers if possible (may depend on build) or the text of relevant line to search for.