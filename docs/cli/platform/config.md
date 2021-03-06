## `ern platform config <key> [value]`
#### Description
* Get or set the local platform configuration values stored in the `~/.ern/.ernrc` file  

#### Syntax
`ern platform config <key> [value]`  

#### Remarks
* The `ern platform config <key> [value]` command is rarely used.  
* All current configuration values are already set and retrieved transparently through the use of commands that rely on the local platform configuration.  
* If a value is not provided, the `ern platform config <key> [value]` command reads the value associated with the specified key and logs it in the terminal.  
* If a value is provided, the `ern platform config <key> [value]` command sets the value associated with the given key with the specified value, overwriting any existing value stored for this key.
