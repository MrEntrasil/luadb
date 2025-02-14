## Usage
```lua
db:exists(id: any, key: any) -> boolean
```
## Example
```lua
local luadb = require('luadb')
local db = luadb.new('main')
local exists = db:exists('users', 'Pablo')

print('Is Pablo a user? '..tostring(exists))
```