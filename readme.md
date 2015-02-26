# Generating Passwords Using What3Words

One of my favorite XKCD comics is [about passwords](http://xkcd.com/936/). Specifically, rather than some complicated symbol/number/character mess, why not just choose three random words and make that your password?

Seemingly unrelated, [what3words](what3words.com) is a location service that converts lat/long coordinates into three words. So instead of a long list of numbers, a location can be marked as "petal fumes night" or "loving loving sofa."

I decided to make a password generator using what3words.

This function generates a random latitude and longitude coordinate pair, and uses the what3words API to generate three words to use as a password. The function also has the option of appending a number and/or character, and an option for adding capital letters.

The script is in iPython notebook format, but you can view it on [iPython notebook viewer site](http://nbviewer.ipython.org/github/chrisalbon/what3words_password_generator/blob/master/password_generator.ipynb).

Note: This is really just a thought experiment and an excuse for me to try out [what3words' API](what3words.com). If you are storing national secrets, you might want to use something else.
