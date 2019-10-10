# What is this?

Get perfect shadow every time for the non-designer.

# Installation

`npm i shadowizard --save`

Then...

``` js
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
})
```

Shadowizard support 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)