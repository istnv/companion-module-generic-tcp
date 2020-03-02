**Generic TCP (Telent)**

This is a generic command module.

If you are using the `Command` action, all serial data is passed through without interpretation or conversion with optional line termination added.

If you use the `HEX based command` action, the hex values you enter will be converted and sent as binary data. The line termination option is not added to HEX commands.

There is a configuration option to change how the commands are terminated to give you flexibility depending on application requirements:

  * Option 1: No Termination, does not alter your command at all.
  * Option 2: `\r` Carriage Return
  * Option 3: `\n` Line Feed
  * Option 4: `\r\n` Carriage Return and Line Feed

