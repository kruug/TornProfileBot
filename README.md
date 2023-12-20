# TornProfileBot
A place to gather issues and enhancements for Torn Profile Bot.

Currently, the commands are as follows:

/profile: takes either a Discord user tag or a Torn ID. Returns profile information on that user, assuming they are verified in the official Torn Discord server
/AddKey: takes a Torn API key. This can be a Public Only key as it's only used to gather public information regarding users. These are kept in an SQL database and retrieved in random order to prevent overloading an individual's API usage.
