# SKBungeeBrigdeAPI
easy to use BungeeBridge plugin api

# required addons:  
  * skript 2.6
  * skript-reflect
  * [BungeeBridge](https://www.spigotmc.org/resources/bungeebridge.5820/)

# API:  
  * bungee_getplayerlist(server:string)  
    get all online players from server  
    > return type: string list  
    option: server - bungee server name , "none" = all servers  
    
  * bungee_getserverlist()  
    get all online servers from bungeecord  
    > return type: string list  
    
  * bungee_playerIsOnline(offlineplayer)  
    > return type: boolean  
    
  * bungee_GetServerByPlayer(offlineplayer)
    get server name by player  
    > return type: string  
    
  * bungee_executecommand(string)
  
  * bungee_writeconsole(string)
    send message to bungee console  

  * bungee_sendplayer(offlineplayer,servername)  

  * bungee_kickplayer(offlineplayer,message)
    
  * bungee_message(offlineplayer,message,type)  
    > type = "raw" or "normal"  
    > raw = json data
    
  * bungee_broadcast(message,type)
    > type = "raw" or "normal"  
    > raw = json data

  * bungee_sendActionBar(offlineplayer,message)  

  * bungee_sendTitle(offlineplayer,title,subtitle,staytime(seconds))  







  
