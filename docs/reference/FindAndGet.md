## Usage
```lua
db:FindAndGet(id: any, key: any) -> table|nil
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')

-- Getting user table
local userdb = db:FindAndGet('users', 'MrEntrasil')

if userdb then
    print("MrEntrasil's coin: "..userdb.coin)
end
```