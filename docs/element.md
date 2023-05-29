Other components inherit these attributes
>- **void** element:**setX(** *number* **x )** -- This is used internally - although you're able to use it you probably shouldn't.
>- ****number**** element:**getX()** -- This is used internally - although you're able to use it you probably shouldn't.
>- **void** element:**setY(** *number* **y )** -- This is used internally - although you're able to use it you probably shouldn't.
>- **number** element:**getY()** -- This is used internally - although you're able to use it you probably shouldn't.
>- **void** element:**setW(** *number* **width )** -- This is used internally - although you're able to use it you probably shouldn't.
>- **number** element:**getW()** -- This is used internally - although you're able to use it you probably shouldn't.
>- **void** element:**setH(** *number* **height )** -- This is used internally - although you're able to use it you probably shouldn't.
>- **number** element:**getH()** -- This is used internally - although you're able to use it you probably shouldn't.
>- **number**, **number** element:**getAbsolutePos()** -- This is used internally - although you're able to use it you probably shouldn't.
>- **void** element:**setParent(** *element*)** -- This is used internally - although you're able to use it you probably shouldn't. ***CAN CRASH***
>- **void** element:**setPos(** *number* **x,** *number* **y ) or setPos( Vector(x,y) )** -- set the position relative to the parent element
>- **number**, **number** element:**getPos()** -- get the position relative to the parent element
>- **void** element:**setSize(** *number* **width,** *number* **height ) or setPos( Vector(width, height) )** 
>- **number**, **number** element:**getSize()** 
>- **number**, **number**, **number**, **number** element:**getBounds()** -- get the bounds relative to the parent element
>- **void** element:**dockPadding(** *number* **x,** *number* **y,** *number* **w,** *number* **h )** -- [gmod wiki](https://wiki.facepunch.com/gmod/Panel:DockPadding)
>- **void** element:**dockMargin(** *number* **x,** *number* **y,** *number* **w,** *number* **h )** -- [gmod wiki](https://wiki.facepunch.com/gmod/Panel:DockMargin)
>- void element:**SetVisible(Bool)** - Whether a component and it's children should be rendered
>- bool element:**isVisible()** - Whether a component and it's children should be rendered
