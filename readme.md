# Generating Passwords Using What3Words

One of my favoriate XKCD comics is [about passwords](http://xkcd.com/936/). Specifically, we not just chose three random words and make that your password?

Seemingly unrelated, [what3words](what3words.com) is a location service that converts lat/long coordinates into three words.

I decided to make a password generator using what3words. So instead of a long list of numbers, a location can be marked as "petal fumes night" or "loving loving sofa."

This script generates a random latitude and longitude coordinate pair, and uses the what3words API to generate three words to use as a password. The function has the option of appending a number or character as needed.

Note: This is really just a thought experiment and an excuse for me to try out [what3words' API](what3words.com). If you are storing national secrets, you might want to use something else.
