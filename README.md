# spwn-dye
Coloured strings in SPWN using unicode characters.

Requires: latest compiled version of spwn.

## Use
Add library to `libraries` folder in your project (or use pckp whenever it's done)

```rs
import "spwn-dye"

let string = @dye::from("I am red string", fore=@dye::FORE.RED)
let another_string = @dye::from("I am blue string", fore=@dye::FORE.BLUE)

string.append(another_string)

$.print(string)
```
