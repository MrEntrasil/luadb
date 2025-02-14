## Usage
```lua
db:FindAndSet(id: any, key: any, tab: table) -> nil
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')

-- Changing values
db:FindAndSet('users', 'MrEntrasil', {
    coin = 0,
    id = 29108312
})
```