# List of functions & usage

### Send a title with subtitle

```getTitle("TITLE", "SUBTITLE", player)```

*Want to make it an argument? Do it like this:*

```getTitle(arg-1, arg-2, player)```

### Send an actionbar message

```getActionbar("MESSAGE", player)```

### Set the world time

```getTime("DAY/NIGHT")```

### Teleport a player to another player

```getTeleport(PLAYER, PLAYER)```

*eg: getTeleport(player, Notch), this will teleport the executor to a player called "Notch"*

### Get number of online players

```getOnline(player)```

### Get names of online players

```getOnlineNames(player)```

## CYOM *(requires CreateYourOwnMenu plugin)*

### Open a menu

```cyomMenuOpen("MENU", player)```

### Edit a menu

```cyomMenuEdit("MENU", player)```


## ASkyBlock *(requires ASkyBlock plugin)*

### Open the Island Create Menu

```asbIsCreate(player)```
