# Hammerspoon Configs

## Hammerspoon

[Download here.](http://www.hammerspoon.org)

## Installation
'''shell
cp -r ~/.hammerspoon ~/hammerspoon_bac
git clone git://github.com/hit1024/oh-my-hammerspoon.git ~/.hammerspoon
'''

## Hotkey Definition By Convention

- drible: ctrl + cmd
- dribleShift: ctrl + cmd + shift
- prefix: ctrl + alt
- prefixShift: ctrl + alt + shift
- hyper: ctrl + alt + cmd
- hyperShift: ctrl + alt + cmd + shift

## Features

- Switch to certain app. 
    - `drible` + lowercase key
    - `dribleShift` + uppercase key
- Quick resize current window.
    - leftTop: `hyper` + u
    - rightTop: `hyper` + i
    - leftBottom: `hyper` + j
    - rightBottom: `hyper` + k
    - leftHalf: `hyper` + h
    - rightHalf: `hyper` + l
    - fullScreen: `hyper` + f
    - centerScreen: `hyper` + c
- Move current window horizontally, or vertically.
    - upMove: `hyper` + up
    - downMove: `hyper` + down
    - leftMove: `hyper` + left
    - rightMove: `hyper` + right
- Adjust the size of current window. 
    - upExtend: `hyperShift` + up
    - downExtend: `hyperShift` + down
    - leftExtend: `hyperShift` + left
    - rightExtend: `hyperShift` + right
- Move current window to another monitor.
    - toWest: dribleShift + left
    - toEast: dribleShift + right
- Adjust windows for current app mode. `hyper` + `down` enter the mode. In the mode `left`, `right` adjust window, `up`, `down` switch window.
- Undo.
    - `hyper` + `z`
- Auto adjust apps when an app is just launched or a new monitor is plugged/removed.
- Caffeinate. 
    - dribleShift + `c`
- Auto reload configs.

## Regards

@songchenwen https://github.com/songchenwen/dotfiles/tree/master/hammerspoon

Mainly based on his work, i just add some specific resizing code.