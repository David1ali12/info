 Command                      | Usage
------------------------------|-----------------------------------------------------------------------------------------------
help                          | Shows list of commands
split [id] [count]            | Splits a player
ban [ip]                      | bans the player
unban [ip]                    | Unbans an IP
kickbot [number]             | Kill a specific number of bots. (_Leave blank to kill all_)
merge [id]                     | Forces a player to merge
addbot [number]                | Adds [Number] of bots to the server. If an amount is not specified, 1 bot will be added.
board [String 1] [String 2] ...| Replaces the text on the leaderboard with the string text.
boardreset                     | Resets the leaderboard to display the proper data for the current gamemode
change [config setting] [value]| Changes a config setting to a value. (Usage: **change serverMaxConnections 32**).Note that some 
clear                          | Clears the console output
color [id] [r] [g] [b]         | Replaces the color of the specified player with this color.
exit                           | Closes the server
kick [id]                      | Kicks a specific player -or- bot from the server
kill [id]                      | Kills all cells belonging to a specific player
mass [id] [mass]               | Sets the mass of all cells belonging to a specified player.
name [id] [new name]           | Changes the name of the player with the specified id with [New Name].
pl                   | Shows a list of connected players, their IP, player ID, the amount of cells they have, total mass, and their position.
pause                          | Pauses/Unpauses the game
reload                         | Reloads the config file used by the server. However, the following values are not affected: 
st                         | Shows the amount of players currently connected, time elapsed, memory usage (memory used/memory allocated), and the current gamemode.
tp [id] [x pos] [y pos]        | Teleports the specified player to the specified coordinates.
