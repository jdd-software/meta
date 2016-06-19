#Can I have a dump of rude/abusive comments?

We already know [it is possible](http://meta.stackoverflow.com/questions/280546/can-a-machine-be-taught-to-flag-comments-automatically) for a machine to be taught to flag comments automatically. This incredible post used machine learning techniques with an initial training on known good and flaggable comments in order to classify any comments.

[One of the answers](http://meta.stackoverflow.com/a/280554/1743880) of that post mentioned that it would be even more useful to identify rude / offensive comments automatically with a very high success rate. This is what I intend to try and start.

To do that, I started to use a basic identification technique with a regular expression. This generates too much false positives, and, like the linked post, a machine learning algorithm is needed. However, this means I need a lot of rude / offensive comments to train a classifier. I can look at my comment flag history and filter (with the help of a user script, since it isn't possible directly with the UI) those that I flagged as rude, but there aren't that many.

Bottom-line: I want lots (> 3000) of rude comments. The dump should contain comments deleted by a moderator that has at least one rude/offensive flag.
