# Kaboom Util 

Kaboom Util is a npm package for have access to a lot of Kaboom comps and plugins, in only one package!

**It is recommended to use this package with the latest version of kaboom, it is not guaranteed to work correctly in previous versions**

# Install 

NPM: `npm i kaboom-util`

# Quick Example

```.js
import kutil from "kaboom-util";

kaboom();

add([
    sprite("bean");
    kutil.blink(0.2)
]);

/*
Or you can import a specify component 

import { blink } from "kaboom-util";
*/
```

# Components List

* [blink()]() - Blink your objects
