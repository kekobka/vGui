#StarfallEX GUI
[[TO DO]]
[[multiscreen rendering]]
[[more elements]]

### Components
- [Base](#element)
---

## Short example
```lua
--@name vGui easy example
--@client
--@include vgui/vgui.lua
local vGui = require('vgui/vgui.lua')

local gui = vGui:new("hud") // creating new thread gui
gui:setVisible(true) // set visible on initialize
local res,resy = gui:getResolution() // get resolution for next operations

local mainmenu = gui:add("panel")
mainmenu:setTitle("example")
mainmenu:setSize(res/2,resy/2)
mainmenu:center()
```

## Adding buttons
```lua
--@name vGui easy example
--@client
--@include vgui/vgui.lua
local vGui = require('vgui/vgui.lua')

local gui = vGui:new("hud") // creating new thread gui
gui:setVisible(true) // set visible on initialize
local res,resy = gui:getResolution() // get resolution for next operations

local mainmenu = gui:add("panel")
mainmenu:setTitle("example")
mainmenu:setSize(res/2,resy/2)
mainmenu:center()

local button = gui:add("button",mainmenu) //gui:add(classname, parent or nil, function(newpanel) end or nil)
button:setText("FILL")
button:dock(FILL)

```

---
## Element
Other components inherit these attributes
>- void element:**setX(x)** -- This is used internally - although you're able to use it you probably shouldn't.
>- number element:**getX()** -- This is used internally - although you're able to use it you probably shouldn't.
>- void element:**setY(y)** -- This is used internally - although you're able to use it you probably shouldn't.
>- number element:**getY()** -- This is used internally - although you're able to use it you probably shouldn't.
>- void element:**setW(width)** -- This is used internally - although you're able to use it you probably shouldn't.
>- number element:**getW()** -- This is used internally - although you're able to use it you probably shouldn't.
>- void element:**setH(height)** -- This is used internally - although you're able to use it you probably shouldn't.
>- number element:**getH()** -- This is used internally - although you're able to use it you probably shouldn't.
>
>- void element:**setPos(x, y) or setPos(Vector(x,y))** -- set the position relative to the parent element
>- number, number element:**getPos()** -- get the position relative to the parent element
>- void element:**setSize(width, height) or setPos(Vector(width, height))** 
>- number, number element:**getSize()** 
>- number, number, number, number element:**getBounds()** -- get the bounds relative to the parent element
>- void element:**dockPadding(x,y,w,h)** -- (gmod wiki)[https://wiki.facepunch.com/gmod/Panel:DockPadding]
>- void element**:dockMargin(x,y,w,h)** -- (gmod wiki)[https://wiki.facepunch.com/gmod/Panel:DockMargin]
>- void element:**SetVisible(Bool)** - Whether a component and it's children should be rendered
>- bool element:**isVisible()** - Whether a component and it's children should be rendered


>- element:**scale(factor, recursive or nil)** - Scales the component's size and position by factor (number), and recurses if recursive (boolean), defaults to true
---

