QuantumVim
================
QuantumVim is a vim key-binding add-on for Firefox. It is targeting future Firefox releases with e10s and WebExtension.

![screenshot](https://github.com/shinglyu/QuantumVim/raw/master/doc/screenshot.png)

# Installation
* Open `about:debugging`, click "Load temporary add-on"
* Select the `manifest.json`

# Supported commands
* `j`, `k`: scroll page
* `J`, `K`: switch to previous/next tab
* `r`, `R`: reload page (`R` bypass the local web cache)
* `gg`, `G`: go to the top/bottom of the page
* `H`, `L`: back/forward in history
* When focusing on an `<input>` element. It will automatically enters the INSERT MODE.

# TODO:
* `h`, `l`: scroll
* `:open`: open an URL or search
* `:tabopen`: open an URL or search in a new tab
* `f`: follow links
* `F`: follow links in a new tab
* Insert Mode: pass all keys to `<input>` when focused
* Passthrough Mode: pass all keys to the page

#Contribute
Please feel free to submit PR or issues.
You are suggested to run `jshint *.js` before you submit a pull request. To install jshint you can `npm install -g jshint`.
