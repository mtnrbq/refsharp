# refsharp README

refsharp allows you to add F# references (`#r`) to the current .fsx file by right clicking on a .dll in the explorer window.

## Features
Direct reference insertion (`#r` only)
![useDirectReferences-true](screencap/useDRT.gif)

Include path and reference insertion (`#I` & `#r`)
![useDirectReferences-false](screencap/useDRF.gif)


## Extension Settings

This extension contributes the following settings:

* `refsharp.useDirectReferences`: sets refsharp to use either direct references (#r only), or indirect references (#I & #r)



## Known Issues

No known issues

## Release Notes


### 0.6.0 - alpha

Initial alpha release of refsharp

### 0.7.0 - alpha (Kingsman)

Add configuration item to use either direct references (`#r` only), or indirect references (`#I` & `#r`)