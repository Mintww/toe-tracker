# toe-tracker
A simple discord bot designed to keep track of however long a server can go without referencing toes.

The bot provides a few commands: "!tthelp" which lists all available commands. "!tt" which will tell you how long the server has gone without mentioning toes. "!ttsilence" for which the administrator permission is required, which will silence the bot while active. "!ttalert" which requires the administrator permission and unsilences the bot.

The bot also monitors all messages for a message mentioning toes (specifically, case-insensitive, and accent-insensitive, but not ensuring there are word-breaks on either side of the phrase), and will reset the server's counter if it finds a message containing a match after calling out the user publically. After calling out one user, the bot will silently reset the counter until a half hour has passed since its last callout.

