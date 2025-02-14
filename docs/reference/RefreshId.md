## Usage
```lua
db:RefreshId(id: any) -> nil
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')

-- Refreshing "users" Id
db:RefreshId('users')
```