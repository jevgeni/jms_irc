An IRC-like application implemented using JMS (ActiveMQ and Spring JMS).

Will support the following commands:

create or join a channel:
   /join <channel>

leave current channel:
   /part

kick out the user from channel:
   /kick <channel> <user> <message>

Send a private message:
    /privmsg <nick> <text>

Change nick:
    /nick <new_nick>

List all channels:
    /list

List all users on the channel:
    /names <channel>