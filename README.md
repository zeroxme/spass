# Spass library
automated paddings and margins via Scss/Sass

Advantages:
- Choose your base spacing that matches your design.
- Build your own list of paddings and margins.
- Extend the classes in your other Sass/Scss modules


Follow [@zerox_me](https://twitter.com/zerox_me) for updates.



## Installation:

- Bower

```bash
   bower install spass
```


### Usage:

- Define your base spacing by overriding `$spass-base`.
- Define your spacing sequence by overriding `$spass-array`.
- include the mixin `spass-creator()`


## Spass array structure:
#### Property:
- margin
- padding

#### Class name
- Naming convention is up to you. The used one is `mt-sm` means margin top is small. `p-none` padding is 0

#### Spacing variable
- The value of the margin/padding assigned to the class



## Contribute
if you think that I missed something let me know so we can make it better together :)

reach me on twitter [@zerox_me](https://twitter.com/zerox_me) if you needed any help

## License
Copyright (c) 2015 zero, released under the MIT license