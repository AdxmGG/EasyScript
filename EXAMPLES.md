# List of functions & usage

### Send a title with subtitle

```showTitle("TITLE", "SUBTITLE", player)```

*Want to make it an argument? Do it like this:*

```showTitle(arg-1, arg-2, player)```

### Send an actionbar message

```showActionbar("MESSAGE", player)```

### Set the world time

```setTime("DAY/NIGHT")```

### Teleport a player to another player

```doTeleport(PLAYER, PLAYER)```

*eg: getTeleport(player, Notch), this will teleport the executor to a player called "Notch"*

### Get number of online players

```getOnline(player)```

### Get names of online players

```getOnlineNames(player)```

# CYOM *(requires CreateYourOwnMenu plugin)*

### Open a menu

```cyomMenuOpen("MENU", player)```

### Edit a menu

```cyomMenuEdit("MENU", player)```


# ASkyBlock *(requires ASkyBlock & Essentials plugin)*

### Open the Island Create Menu

```asbIsCreate(player)```

# Vault *(requires Vault plugin)*

### Show player's balance

```vaultShowBalance(player)```

### Add money to player's balance

```vaultAddBalance(AMOUNT, player)```

### Remove money from player's balance

```vaultRemoveBalance(AMOUNT, player)```

# Multiverse *(requires Multiverse plugin)*

### Create world

```mvCreateWorld("WORLDNAME", "TYPE", "PRESET")```*Leave "PRESET" blank for normal world*

### Delete world

```mvDeleteWorld("WORLDNAME")```*

### TP to a world

```mvTpWorld("WORLDNAME", player)```

