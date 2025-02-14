## Usage
```lua
db:Refresh() -> nil
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')

-- Refreshing all database Ids
db:Refresh()
```