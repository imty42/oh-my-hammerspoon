# Hammerspoon Configs

## Hammerspoon

[Download here.](http://www.hammerspoon.org)

## Installation
```shell
# backup old config
mv ~/.hammerspoon ~/hammerspoon_bac

git clone git://github.com/imty42/oh-my-hammerspoon.git ~/.hammerspoon
```
Hammerspoon->Reload Config

## Hotkey Definition By Convention

- `drible`: `ctrl` + `cmd`
- `dribleShift`: `ctrl` + `cmd` + `shift`
- `prefix`: `ctrl` + `alt`
- `prefixShift`: `ctrl` + `alt` + `shift`
- `hyper`: `ctrl` + `alt` + `cmd`
- `hyperShift`: `ctrl` + `alt` + `cmd` + `shift`

## Features

- Switch to certain app. 
    - `prefix`/`prefixShift` + somekey
- Quick resize current window.
    - leftTop: `hyper` + `u`
    - rightTop: `hyper` + `i`
    - leftBottom: `hyper` + `j`
    - rightBottom: `hyper` + `k`
    - leftHalf: `hyper` + `h`
    - rightHalf: `hyper` + `l`
    - fullScreen: `hyper` + `f`
    - centerScreen: `hyper` + `c`
- Move current window horizontally, or vertically.
    - upMove: `hyper` + `up`
    - downMove: `hyper` + `down`
    - leftMove: `hyper` + `left`
    - rightMove: `hyper` + `right`
- Adjust the size of current window. 
    - upExtend: `hyperShift` + `up`
    - downExtend: `hyperShift` + `down`
    - leftExtend: `hyperShift` + `left`
    - rightExtend: `hyperShift` + `right`
- Move current window to another monitor.
    - toWest: `dribleShift` + `left`
    - toEast: `dribleShift` + `right`
- Adjust windows for current app mode. `hyper` + `down` enter the mode. In the mode `left`, `right` adjust window, `up`, `down` switch window.
- Undo.
    - `hyper` + `z`
- Auto adjust apps when an app is just launched or a new monitor is plugged/removed.
- Caffeinate. 
    - `dribleShift` + `c`
- Auto reload configs.
- iTunes control.
    - previous: `dribleShift` + `7`
    - play/pause: `dribleShift` + `8`
    - next: `dribleShift` + `9`
- Volumn control.
    - mute: `dribleShift` + `0`
    - lower: `dribleShift` + `-`
    - louder: `dribleShift` + `+`

## Regards

@songchenwen https://github.com/songchenwen/dotfiles/tree/master/hammerspoon

Mainly based on his work, i just added some specific resizing code.
