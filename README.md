# plugman-z
Add plugins to your server without restarting! (skid of plugman)

### What is PlugmanZ?
*PlugmanZ is a skid of Plugman, which is a plugin that allows you to add plugins to your server without restarting it. However, this plugin has quite a lot of bugs and errors when adding specific plugins. However, this plugin thrives to try fix this.*

### What is Plugman?
*Plugman is a plugin that allows you to add plugins to a server without restarting it. This is useful as sometimes you might have alot of players online and you would need to restart the server to add one specific plugin.*

### Why fork Plugman?
*Plugman is a very useful and good plugin, however, this plugin is quite buggy. For example, if you add a plugin to a 1.13+ server with Plugman, then you will not be able to tab-complete any of it's commands. However, with PlugmanZ, this is fixed.*

### Features:

-   Enable, disable, restart, load, reload, and unload plugins from in-game or console.
-   List plugins alphabetically, with version if specified.
-   Get useful information on plugins such as commands, version, author(s), etc.
-   Easily manage plugins without having to constantly restart your server.
-   List commands a plugin has registered.
-   Find which plugin a command is registered to.
-   Tab completion for command names and plugin names.
-   Dump plugin list with versions to a file.
-   Permissions Support - All commands default to OP.

### Commands + Command Description:

/plugman help Show help information.  
/plugman list [-v] List plugins in alphabetical order. Use "-v" to include versions.  
/plugman info [plugin] Displays information about a plugin.  
/plugman dump Dumps plugin list and versions to a file.  
/plugman usage [plugin] List commands that a plugin has registered.  
/plugman lookup [command] Find which plugin a command is registered to.  
/plugman enable [plugin|all] Enable a plugin.  
/plugman disable [plugin|all] Disable a plugin.  
/plugman restart [plugin|all] Restart (disable/enable) a plugin.  
/plugman load [plugin] Load a plugin.  
/plugman reload [plugin|all] Reload (unload/load) a plugin.  
/plugman unload [plugin] Unload a plugin.  
/plugman check [plugin|all] [-f] Check if a plugin is up-to-date.

### Permissions (Permission Node | Default | Description):
plugman.admin | OP | Allow use of all PlugMan commands.  
  
plugman.update | OP | Allow user to see update messages.  
  
plugman.help | OP | Allow use of the help command.  
  
plugman.list | OP | Allow use of the list command.  
  
plugman.info | OP | Allow use of the info command.  
  
plugman.dump | OP | Allow use of the dump command.  
  
plugman.usage | OP | Allow use of the usage command.  
  
plugman.lookup | OP | Allow use of the lookup command.  
  
plugman.enable | OP | Allow use of the enable command.  
  
plugman.enable.all | OP | Allow use of the enable all command.  
  
plugman.disable | OP | Allow use of the disable command.  
  
plugman.disable.all | OP | Allow use of the disable all command.  
  
plugman.restart | OP | Allow use of the restart command.  
  
plugman.restart.all | OP | Allow use of the restart all command.  
  
plugman.load | OP | Allow use of the load command.  
  
plugman.reload | OP | Allow use of the reload command.  
  
plugman.reload.all | OP | Allow use of the reload all command.  
  
plugman.unload | OP | Allow use of the unload command.  
  
plugman.check | OP | Allow use of the check command.  
  
plugman.check.all | OP | Allow use of the check all comamnd.
