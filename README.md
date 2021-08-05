# Android Studio Tips & Tricks

## Table of contents
* [Android Studio Mac Shortcuts](#shortcuts)
* [Android Studio Setup](#setup)
* [Charles setup on Emulator](#charles)

## Android Studio Shortcuts <a name="shortcuts"></a>

Commands| Description
---------|--------
 | <kbd>shift</kbd> + <kbd>shift</kbd>   | Search everywhere
 | <kbd>&#8984;</kbd> + <kbd>shift</kbd> + <kbd>F</kbd>  | Find in path
 | <kbd>&#8984;</kbd> + <kbd>option</kbd> + <kbd>L</kbd> | Reformat code
 | <kbd>&#8984;</kbd> + <kbd>option</kbd> + <kbd>O</kbd> | Search by class name
 | <kbd>&#8984;</kbd> + <kbd>P</kbd> | Show parameters
 | <kbd>control</kbd> + <kbd>R</kbd> | Build & Run
 | <kbd>&#8984;</kbd> + <kbd>,</kbd> | Preferences
 | <kbd>&#8984;</kbd> + <kbd>K</kbd> | Commit messages to VCS
 | <kbd>&#8984;</kbd> + <kbd>;</kbd> | Project Structure
 | <kbd>&#8984</kbd> + <kbd>1</kbd>  | Toggle project window
 | <kbd>option</kbd> + <kbd>delete</kbd> | Delete to end/start of word
 | <kbd>shift</kbd> + <kbd>F6</kbd>  | Rename
 | <kbd>control</kbd> + <kbd>J</kbd> | Quick doc lookup
 | <kbd>&#8984;</kbd> + <kbd>shift</kbd> + <kbd>&#8593;</kbd>  | Resizing tool window
 | <kbd>shift</kbd> + <kbd>esc</kbd> | Closes the tool window


## Android Studio Setup <a name="setup"></a>

* <ins>Giving theme to Android Studio</ins> : I use Halcyon theme. Go to Preferences -> plugins and search for theme you want to use.
* <ins>Making logs colorful</ins> : Preferences -> Editor -> Color Scheme  ->  Android Logcat
  - Debug: #5CCFE6, Error: #EF6B73, Info: #BAE67E, Warning: #FFD580
* <ins>Configure logcat header</ins>: On the logcat's left panel is the Settings icon. Just 'show tag' is is enough in most cases.
* <ins>Disable unused plugins</ins>: Go to Preferences -> Plugins. I disable Mercurial and Subversion. 
* <ins>Increase Heapsize</ins> Preference -> Heapsize = 3072MB

## Setting up emulator to work with Charles Proxy <a name="charles"></a>
