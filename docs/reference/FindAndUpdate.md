## Usage
```lua
db:FindAndReplace(id: any, key: any, tab: table) -> nil
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')

-- Updating values
db:FindAndReplace('users', 'MrEntrasil2', {
    coin = 100
})
```