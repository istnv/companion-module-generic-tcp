**Generic TCP commands (Telnet)**

This is a generic TCP command module.

If you are using the `Command` action, data is transmitted as entered without interpretation or conversion. You may select to add an optional line termination.

If you use the `HEX based command` action, the hex values you enter will be converted and sent as binary data. The line termination option is not added to HEX commands.

There is a configuration option to change how the commands are terminated to give you flexibility depending on application requirements:

  * Option 1: No Termination, does not alter your command at all.
  * Option 2: `\r` Carriage Return
  * Option 3: `\n` Line Feed
  * Option 4: `\r\n` Carriage Return and Line Feed

