# UltimateReminder

<h1 align="center">
  <br>
  <img src="/ureminder.png" alt="Ureminder Logo" width="350">
  <br>
</h1>
<p align="center">
    <a href="https://discord.gg/yNnnkRfavm" alt="discord">
        <img src="https://img.shields.io/discord/894059728714489856?color=b&label=Discord"/>
    </a>
    <a href="https://twitter.com/memocrackenxd" alt="Twitter">
      <img src="https://img.shields.io/twitter/follow/memocrackenxd?style=social"/>  
    </a>
   <a href="https://github.com/MemocrackenDev" alt="Twitter">
      <img src="https://img.shields.io/github/followers/MemocrackenDev?style=social"/>  
    </a>
</p>

# Why UltimateReminder?

UltimateReminder has a very simple system for 
reminders and it is very easy to configure unlike 
other plugins.

Here is a list of the good things about UltimateReminder:

- Quick setup
- Not heavy
- Easy to use
- Interactive
- Required permissions
- Simple Code
- Database in Config.yml (Modifiable database)
- Few commands
- Modifiable Prefix
- Between many more!

# What is it?

UltimateReminder is a Minecraft plugin to give messages from time to time, this tool 
can be very useful if you want a server with constant memories.

# Config.yml Help

<p align="center">
 - [Config.yml Default Config](https://ghbtns.com)
</p>

Looking for help with setup? You are in the right place

- Enable or Disable

This option is created to enable or disable the pluing action

```yml
config:
  # true > Plugin Working / false > The plugin will not be working
  enable: true
```

- Prefix

This option is created to change the prefix of each ad, for example if the plugin gives 
the ad by default it will be like this:

**[UReminder] Memocracken its the best because its my creator!**

In the configuration you can change this method, this is an example:

**[DMC] Memocracken its the best because its my creator!**

```yml
config:
  prefix: "&f[&6UReminder&f] "
```

And if it were the second option it would be like this:

```yml
config:
  prefix: "&f[&DMC&f] "
```

and so on for any prefix you want.

- Cooldown

The Cooldown is created to pause between Reminders, for example so that all the Reminders do 
not appear at the same time (in an endless loop) I put a default cooldown of one 
minute, you can change it in the configuration to make it more manipulable

***Note:*** *Soon I will change this but for example if you want to put a second you have to put it with an extra zero, for example if I want to put a minute and thirty seconds I would have to put "900" in the cooldown section, it can be confusing but that's the way in which we handle this, another example is that if I want to put thirty seconds then I have to put "300", the same for two minutes: "1200", if you have doubts do not hesitate to tell me through Discord*

```yml
config:
  cooldown: 600 # > 1 minute / 1200 > 2 minutes / Etc.
```
This can be changed freely but always remember to put a zero, I explain this in detail in the note above.

- Random Messages

This area is the most important part of the plugin since here are the Reminders that are placed on the server from time to time

If you want to know how it works because you are in the right place, this area is easy to use to create one manually (from config.yml) you just have to put a "-" below the reminders created by default (you can delete them) 

```yml
config:
    Random-Messages: 
    # Default messages (You can delete/edit them)
    
    - "&3%Player% remember to have some fun with the &6server name&3!"
    - "&3Remember that hacks are not tolerated in &6Server Name"
    - "&3&lRemember to invite your friends!"
    
    # The characters below are created by the command "/ureminder create" or by someone else
    
    - "&3This is a Test! &lJoin to my Discord server!"
```

but yes you do not understand that function well just put in the chat of your server 

```
/ureminde
r create Your-Arguments
```

If you wonder where these arguments are located then the answer is in "config.yml", in the same area of "Random-Messages" every time that command is executed it will change and put what you put, remember that they work the same the color codes in yml

# You have more questions?

You can ask us any questions on our Discord server and we will answer them with pleasure!

# Error or bug?

If you found any error or bug, we would appreciate if you tell us what the error is, you can contact us on Twitter or Discord
