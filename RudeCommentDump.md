#Can I have a dump of rude/abusive comments?

We have [bot](http://stackapps.com/questions/6910) that currently is elaborating **all** comments on SO to find possibile duplicates and notify hammers in tag.

While elaborating all comments, I also for testing reasons started to try to find the rude/offensive comments (hence I'm already parsing them all so why not). Currently it is implementing [SmokeDetector](https://github.com/Charcoal-SE/SmokeDetector) regex with only minor changes.

This regex if fairly good to find offensive comments if they contain swear words, however I would like to explore the possibilities to find rude/offensive comments that do not contain these words (regex/machine learning etc)

The dump should contain what was nuked by mods and had atleast one rude/offensive flag. There is no need to included the user who posted the comment, but their reputation could be interesting.

I know other users that are also  interested in a similar dump.

http://chat.stackoverflow.com/transcript/message/31044541#31044541








