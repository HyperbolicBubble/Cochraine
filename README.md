# Cochraine
*Enhancing your streaming experience*
## About Cochraine
Cochraine is an IRC bot for the Twitch network. It has run-time management for plugins 'pods', that are written in Lua. This means you can load your pods, or unload them whilst running. Therefore minimising downtime, and not affecting your streams!

## Live version
We host our own Cochraine, which is available globally throughout the twitch network.

To get Cochraine on your channel, go to: http://twitch.tv/hyperbolicbubble and enter in chat: `!invite`. If you want the bot to go into a different channel, type the name afterwards with a space i.e. `!invite hyperbgod`. From there type `!help` for further information.

*If you want your pod to be supported, send a link to your source code, to admin@hyperbolicbubble.com.*

## Configuration
Making it so number one, could never be easier (we tried to think of a way, but this is about minimal setup as it gets).

Just alter the configuration file, which should look something like below:
```
Configuration file = example
```
Then run it! Couldn't be simpler, could it? (Oh, and make sure you're not sufficating it with closed ports).

## Building your own pod
Much like Voyager, we host the facilities for you to build your own pod if you're not happy with the fleet issued ones.

All received messages are put into an internal message queue system, which is then distrubuted via event emitters to all the loaded pods.

## Links
* [Cochraine Live main channel](http://twitch.tv/hyperbolicbubble)
* Cochraine Live commands
* [Ensign: How to make a Mk. I Pod.](https://github.com/HyperbolicBubble/Cochraine/wiki/Ensign:-Making-a-Mk.-I-Pod)
* [Pod Scrap Yard (API Documentation)](https://github.com/HyperbolicBubble/Cochraine/wiki/Pod-Scrap-Yard)
* [Star Chart (Road Map)](https://github.com/HyperbolicBubble/Cochraine/wiki/Star-Chart)
* [Stellar Cartography (Cochraine Live statistics)](https://github.com/HyperbolicBubble/Cochraine/wiki/Stellar-Cartography)

## Notes
Cochraine will announce itself when joining a channel, but will be silent from there on until the channel owner permits it to start. This is to prevent it be used accidentally, or as a tool to harass people.

The live verison of Cochraine reports statistics of usage, and where it currently is to us. This is annonymous data. This is just to help gauge used features, and prioritise developement areas.

We're available for support on the hyperbolicbubble twitch channel, and our private IRC `localch.at:6667 #hbb`. This is not a dedicated Cochraine support channel.

## License
Copyright 2012 HyperBolic Bubble.

This file is part of Cochraine.

Cochraine is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Cochraine is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Cochraine. If not, see http://www.gnu.org/licenses/.