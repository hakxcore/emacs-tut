<p align="center">
  <img src="https://raw.githubusercontent.com/MUKESHKUMAR2001/emacs-tut/main/media/emacs-tut.png" width="200" height="200"/>
</p>
<p align="center">
<a href="#"><img title="emacs-tut" src="https://img.shields.io/badge/-%20EMACS TUTORIAL-green%3FcolorA%3D%2523ff0000%26colorB%3D%2523017e40"></a>
</p>
<p align="center">
<a href="https://github.com/MUKESHKUMAR2001"><img title="Author" src="https://img.shields.io/badge/Author-mukesh%20kumar-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/MUKESHKUMAR2001/followers"><img title="Followers" src="https://img.shields.io/github/followers/MUKESHKUMAR2001?color=blue&style=flat-square"></a>
<a href="https://github.com/MUKESHKUMAR2001/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/MUKESHKUMAR2001/emacs-tut?color=red&style=flat-square"></a>
<a href="https://github.com/MUKESHKUMAR2001/emacs-tut/network/members"><img title="Forks" src="https://img.shields.io/github/forks/MUKESHKUMAR2001/emacs-tut?color=red&style=flat-square"></a>
<a href="https://github.com/MUKESHKUMAR2001/emacs-tut/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/MUKESHKUMAR2001/emacs-tut?label=Watchers&color=blue&style=flat-square"></a>
<a href="#"><img title="UNMAINTENED" src="https://img.shields.io/badge/UNMAINTENED-YES-blue.svg"</a>
</p>

# emacs-tut
Throughout this tutorial we will use `C` to refer to the key (`CTRL`)
and `M` to refer to the meta key (`Alt`). On most systems, `ALT` or `ESC`
correspond to `M`. On macOS, the Terminal application can be configured
to use `OPT` (`option`) as `M`.

| Name  | Key |                Usually                  |
|-------|-----|-----------------------------------------|
|Control| `C` | `CTRL`                                  |
| Meta  | `M` | `ESC`, `ALT`, `OPT`                     |
|hyphen | `-` | `-` is a connector means `C-p` => `CTRL+p`|

<br>
<br>
<br>

## Curssor Moving Commands

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-p`| Go to Previous line                                        |
|`C-n | Go to next line                                            |
|`C-b`| Go backward in line                                        |
|`C-f`| Go forward in line                                         |
|`M-f`| Move forward in line word by word                          |
|`M-b`| Move backward in line word by word                         |
|`C-a`| Move to the begining of the line                           |
|`C-e`| Move to the end of the line                                |
|`M-<`| Move to the beginning of the whole text                    |
|`M->`| Move to the end of the whole text                          |
|`C-u 8`| Go forward by 8 characters                               |

<br>
<br>
<br>

## Change Mode of emacs


| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`M-x text-mode`| Change mode to the text mode                     |
|`M-x <any-other-text-mode>` | There is many modes in emacs just find help |
|`M-x fundamental-mode`| Change mode to the fundamental mode       |
  
  
<br>
<br>
<br>


## Delete Text Commands

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-spacebar`| To select the text                                   |
|`C-w`| To delete the selected text                                 |
|`C-y`| To reinsert the killed or deleted text (yanking)            |
|`M-y`| To reinsert the killed or deleted text (yanking)            |
|`C-d` | To delete the next character                               |
|`M-d` | To delete the next word                                    |
|`C-k`| To delete the whole line after currsor                      |

<br>
<br>
<br>


## Do Undo

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-/`| Undo                                                       |
|`C-_`| Undo                                                       |
|`C-x_u`| Undo                                                     |

<br>
<br>
<br>


## Find Files

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-x-C-f`| To find a file                                         |
|`C-x-C-s`| To save the file                                       |
|`C-x-C-b`| To get the buffer list                                 |
|`C-x-1`| To ger rid of buffer list                                |

<br>
<br>
<br>


## Autofill

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`M-x auto-fill-mode`| Turn on autofill mode                       |
|`M-x auto-fill-mode`| Turn off autofill mode                      |

<br>
<br>
<br>

## Searching

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-s`| Search Increasing order                                    |
|`C-s`| Continousily search for next, next and next                |
|`Backslash`| For come back on searched words                      |
|`Enter` or `C-g`| For terminate the search                        |        |
|`C-r`| To search in reversing order                               |

<br>
<br>
<br>

## Multiple Windows

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-x-1`| To delete all wondows except one on which you are        |
|`C-x-2`| To split a window into two windows                       |
|`C-x-o`| To move into windows                                     |
|`C-x-0`| To move to the first window                              |
|`C-x-1`| Get rid of top window                                    |
|`C-x-52`| To produce a new frame(window)                          |
|`C-x-50`| To get rid of new frame                                 |

<br>
<br>
<br>

## Others 

  
| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`M-x replace-string`| To replace a string with other              |
|`C-l-C-l`| Bring the line to the top of the screen                |
|`C-h-m`| To see how the text mode is different from fundamental mode|
|`C-x-1`| To remove documentation from screen                        |
|`C-g`| To stop a command of get rid of any thing(It is like `esc`)|
|`C-x-1`| Kill all other windows except on which you are           |
|`C-u`| Inseart                                                    |

<br>
<br>
<br>


## Help

| Key |                       Work                                 |
|-----|------------------------------------------------------------|
|`C-h`| Emacs will show help                                       |
|`C-h-k-C-p`| Get help and whole information about `C-p` Command   |



  
  
  
  
  
