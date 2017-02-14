#PrivateVoiceBot

This is a bot made with Golang for Discord for making ephemeral (temporary) private voice channels.

It was built with user simplicity in mind, in both set-up and execution.

## How to set up the bot

1. Download `main.go`

2. Place it in a nice folder all by it's lonesome.

3. Make sure you have (at least):

    1. [Go](https://golang.org/) 1.7.4
    
    2. [Discordgo](https://github.com/bwmarrin/discordgo) 0.15.0
    
    3. [go-ini](https://github.com/go-ini/ini)
   
4. Run `go build main.go`

5. Open up a console and run `main.exe`/`main` (Windows / Unix-based)

6. Edit the generated settings.ini with your token and any other settings you might want to change

7. Run `main.exe`/`main` again

8. Join the bot to your server and you are set! :)

    1. If you don't know how to do that, you might want to look at a more robust guide.
    
        1. A good example is the [FAQ from @Just-Some-Bot 's MusicBot. (link)](https://github.com/Just-Some-Bots/MusicBot/wiki/FAQ)
        
## How to use the bot in a server

(Here, I assume the prefix is set to the default of `!`)

 - !new [name]
 
    - Makes a new Private Voice channel (if you're not in one/don't already own one)
    
    - If a name is given, use that name for the channel
    
 -  !invite @person...
 
    - Invites users who are mentioned
    
    - Can mention more than one at a time
    
 - !op @person... (NEED OP/OWNER PERMS)
    
    - Gives a user perms similar to the owner.
    
    - Can mention more than one at a time
    
 - !deop @person... (NEED OP/OWNER PERMS)
    
    - Revokes said perms.
    
    - Can mention more than one at a time
    
 - !remove @person... (NEED OP/OWNER PERMS)
 
    - Removes a person from a voice channel
    
    - Can mention more than one at a time
    
 - !delete (NEED OP/OWNER PERMS)
 
    - Deletes the voice channel
        