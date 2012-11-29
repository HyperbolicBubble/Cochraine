Risa
====

C++. TwitchIRC Bot with run-time plugin support written in Lua.

Making it so number one could never be easier (we tried to think of a way, but this is about minimal setup as it gets).

Just alter the configuration file, which should look something like below:

Configuration file = example
Then run it! Couldn't be simpler, could it? (Oh, and make sure you're not sufficating it with closed ports).

Built-in features
One of the goals is to make this bot as flexible as possible, however feature rich too! That's where the lovely exentison system comes into play.

User management system - make sure the right people, execute the right commands.
Runtime plugin management
Reducing downtime is important on busy networks. People rely on your bots for the sake of their channel. It's also important to get plugins out in a timely fashion with minimal complexity. That's why we have chosen Lua as the scripting language and taken it from there.

Todo.

Update management
The hassle and pain of updating IRC services shouldn't be multiplied with IRC bots. That's why updating Risa couldn't be simplier. That is, if you wish to update!

In addition to this, there's functionality enabled for updating plugins as well - as well as installing! Modelled on apt-get and npm, the aim is to get this beauty up and running in no time.

Included plugins
There's some very commonly used irc bot features included, to reduce the startup hassle.

RSS feed syndication

Streaming-site integration

MySQL database layer

Flatfile or database settings