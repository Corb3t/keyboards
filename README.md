<p align="center">
  <img width="268" height="396" src="https://imgs.xkcd.com/comics/borrow_your_laptop.png">
</p>

## keyboards [![Thanks](https://bit.ly/saythankss)](https://github.com/sponsors/corb3t)
This is my keyboard. There are many like it, but this one is mine. My keyboard is my best friend. It is my life. I must master it as I must master my life.

I got sick of keeping track of all the custom keyboard shortcuts and trackpad gestures that I've created, so I decided to create this guide to make setting this up a little easier down the road. If you think my keyboard shortcuts could be improved upon in some way, do not hesitate to contact me.

Table of Contents
- [To Do](#to-do)
- [macOS Spotlight](#macos-spotlight)
- [Setup](#setup)
  - [Disable Spotlight Keyboard Shortcut](#Disable-Spotlight-Keyboard-Shortcut)
  - [Capslock is a Waste](#capslock-is-a-waste)
- [Keyboard Snippets / Text Replacements](#keyboard-snippets--text-replacements)
- [macOS/iOS Text Replacement](#macos/iios-text-replacement)
  - [macOS Text Replacement Setup](#macos-text-replacement-setup)
- [Windows Management](#windows-management)
  - [Rectangle App](#rectangle-app)
    - [Rectangle Keyboard Shortcuts](#rectangle-keyboard-shortcuts)
    - [Rectangle Windows Snapping](#rectangle-windows-snapping)
- [Search Bars](#search-bars)
  - [Alfred](#alfred)
    - [Clipboard History](#clipboard-history)
    - [Alfred Keyboard Snippets](#alfred-keyboard-snippets)
      - [Alfred Keyboard Snippets Setup](#alfred-keyboard-snippets-setup)
    - [Raindrop](#raindrop)
  - [Other Applications](#other-applications)
    - [1Password](#1password)
      - [1Password Keyboard Shortcut Setup](#1password-keyboard-shortcut-setup)
    - [Karabiner](#karabiner)
      - [Karabiner Setup](#karabiner-setup)
    - [iTerm2](#iterm2)
      - [iTerm2 Keyboard Shortcut Setup](#iterm2-keyboard-shortcut-setup)
    - [Fantastical](#fantastical)
      - [Fantastical Keyboard Shortcut Setup](#fantastical-keyboard-shortcut-setup)
    - [Cleanshot](#cleanshot)
      - [Cleanshot Keyboard Shortcut Setup](#cleanshot-keyboard-shortcut-setup)
- [Trackpad Gestures](#trackpad-gestures)
  - [Browser Gestures](#browser-gestures)
  - [Finder Gestures](#finder-gestures)
- [Hire Me](#hire-me)
- [Special Thanks](#special-thanks)

## To Do
 * [Raycast](https://www.raycast.com/) section - Alfred alternative - try it out!
 * Alfred config w/ workflows/snippets/gestures already setup
 * BetterTouchTool config file w/ gestures/shortcuts setup
 * Shell script to auto-install everything
 
## macOS Spotlight
[![Image of macOS Spotlight](https://i.postimg.cc/GmFP1mwG/Clean-Shot-2022-07-19-at-17-44-25-2x.png)](https://postimg.cc/gx0LVd02)

[![Spotlight Menubar Icon](https://i.postimg.cc/P5sc4JQw/Clean-Shot-2022-07-19-at-17-57-02-2x.png)](https://postimg.cc/zV70DJMz)
Have you ever used [Spotlight](https://support.apple.com/guide/mac-help/spotlight-mchlp1008/mac)? It's the little magnifying glass in the top right corner. It's a really fast and convenient way to open apps, files, or even the web. It's even built into [iOS](https://support.apple.com/en-us/HT201285).

By default, you can quickly bring up Spotlight on your mac by pressing:

<kbd>⌘ Command</kbd> + <kbd>Space</kbd> 

In my opinion, using spotlight search is the **fastest way** to navigate around a computer system, including desktop and mobile devices. Instead of navigating through folders manually, searching is often the fastest - how many times have you used Google to navigate to a website you knew the address to? Search will always be faster!

## Setup
If you're willing to download some extra applications, we can create custom keyboard shortcuts that give you access to all sorts of things - a clipboard manager, application launcher, password manager, and more. While Spotlight is really powerful, there are some better tools out there.

The following applications either facilitate the setup of keyboard shortcuts or have a keyboard shortcut that can easily be accessed. Many of these app's dock icons are hidden in my menubar.

* [Alfred 5](https://www.alfredapp.com/) - Save countless hours by using hotkeys, keywords and customizing how you want to search your Mac and activity history. Replaces macOS Spotlight. Utilized below in [Alfred Keyboard Snippets](#alfred-keyboard-snippets), [Clipboard History](#clipboard-history), [Raindrop](#raindrop), and more.

* [BetterTouchTool](https://folivora.ai/) - The must-have application for setting up custom keyboard shortcuts and trackpad gestures. Required for [trackpad gestures](#trackpad-gestures) below.

### Disable Spotlight Keyboard Shortcut
Fortunately for us, Alfred provides us with added functionality, so we will replacing Spotlight's keyboard shortcut with Alfred. To do so, you will need to go to:

```
System Settings > Keyboard > Keyboard Shortcuts > Spotlight Set both to "Off"
```

[![gif of turning off Spotlight's keyboard shortcut](https://i.postimg.cc/BbG31pbj/Clean-Shot-2022-07-19-at-18-08-49.gif)](https://postimg.cc/Hc3RqQQm)

### Capslock is a Waste
How often do you actually use your capslock key? Chances are, it isn't often, so let's remap it to something more useful. Natively within iOS, you can change it to <kbd>⌘ Command</kbd> or <kbd>Esc</kbd>, which are often more useful. If you're feeling more adventurous, I'd highly recommend installing [Karabiner](#karabiner) (with my custom config in this github) to further modify your Capslock key.

To do so, you will need to go to:

```
System Settings > Keyboard > Keyboard Shortcuts > Modifier Keys > Set to "Off" or "Command"
```

[![gif of changing capslock key to somethiing more useful](https://i.postimg.cc/0jttq5T9/Clean-Shot-2022-07-19-at-18-13-22.gif)](https://postimg.cc/ctn7RW1z)

### Keyboard Snippets / Text Replacements
Keyboard snippets, or text replacements allow a user to quickly auto-fill information with a few simple keystrokes. This functionality is built natively into macOS and [iOS](https://support.apple.com/guide/iphone/use-text-replacements-iph6d01d862/ios), but [Alfred](#alfed) offers more powerful options.

#### macOS/iOS Text Replacement
macOS offers it's own "Text Replacements" natively within macOS, which are great because they sync to your iOS devices. They can be setup by navigating to:

```
System Settings > Keyboard > Text Input > Text Replacement
```

##### macOS Text Replacement Setup
[![Gif of my text replacements within macOS](https://i.postimg.cc/dt0XNGGg/Clean-Shot-2022-07-19-at-17-02-13.gif)](https://postimg.cc/qg9jzhbG)

I personally use both types of keyboard snippets/replacements - native due to the iOS syncing, and Alfred because I like to query and review them from Alfred's search bar (Command + Spacebar).

## Windows Management
If there's one thing Microsoft Windows gets right out of the box, it's [Windows Snapping](https://docs.microsoft.com/en-us/windows/apps/desktop/modernize/apply-snap-layout-men). Unfortunately macOS's windows snapping isn't as good, which is why I recommend downloading [Rectangle](https://rectangleapp.com/).

### Rectangle App
Rectangle offers a wide range of customizable Windows snapping options, but I largely use it two ways:

* To quickly snap windows to the top/left/bottom/right using <kbd>⌘ Right Command</kbd> + <kbd>▲ ▼ ◀ ▶ Arrow </kbd> keys (see below).
* To quickly snap windows using my trackpad by clicking and dragging a window
* To quickly move windows from one display to the next (when using external displays)

#### Rectangle Keyboard Shortcuts
[![Gif of Rectangle keyboard shortcuts being used.](https://i.postimg.cc/gkBHvpXh/Clean-Shot-2022-07-21-at-14-00-37.gif)](https://postimg.cc/zVKhr9kD)

Since I try and keep my hands on the keyboard at all times to improve productivity, I have mapped the following shortcuts to my keyboard:

> Snap Window to Top Half: <kbd>⌘ Command</kbd> + <kbd>▲ Up Arrow</kbd>
>
> Snap Window to Bottom Half: <kbd>⌘ Command</kbd> + <kbd>▼ Down Arrow</kbd>
>
> Snap Window to Left Side: <kbd>⌘ Command</kbd> + <kbd>◀ Left Arrow</kbd>
>
> Snap Window to Right Side: <kbd>⌘ Command</kbd> + <kbd>▶ Right Arrow</kbd>

[![Rectangles Window Snapping Keyboard Shortcut Settings](https://i.postimg.cc/g0HBv0CD/Clean-Shot-2022-07-21-at-14-43-30-2x.png)](https://postimg.cc/DWmgh7yJ)

#### Rectangle Windows Snapping
Rectangle also offers similar functionality to Windows by allowing the user to "throw" or "snap" a window. This is on by default.

[![Gif of Rectangle Windows Snapping](https://i.postimg.cc/ZnXgsdsk/Clean-Shot-2022-07-21-at-14-18-09.gif)](https://postimg.cc/7JMmffyX)

## Search Bars

### Alfred
[![Alfred search bar preview](https://i.postimg.cc/Jz460dVY/Clean-Shot-2022-07-19-at-14-18-42-2x.png)](https://postimg.cc/qzSXZw72)

Like spotlight search, but better. Alfred has a long list of features. Alfred is activated by pressing <kbd>⌘ Command</kbd> + <kbd>Space</kbd> 

### Clipboard History

<kbd>⌥ Option</kbd> + <kbd>X</kbd>

I use the clipboard history to easily copy and paste images and text anywhere.

[![Alfred's Keyboard History Searchbar](https://i.postimg.cc/hvrsPSfZ/Clean-Shot-2022-07-19-at-14-01-59-2x.png)](https://postimg.cc/H8rX610b)

#### Alfred Clipboard History Setup
[![Alfred's Clipboard History Setup Screen](https://i.postimg.cc/8CzS15c9/Clean-Shot-2022-07-19-at-13-58-43-2x.png)](https://postimg.cc/CRXt7wjs)

### Alfred Keyboard Snippets
<kbd> ⌥ Option </kbd> + <kbd>S</kbd>

Great for quickly filling in information you regularly use like e-mails, dates, and links.

[![Alfred's Keyboard Snippet Searchbar](https://i.postimg.cc/65cbBhZ6/Clean-Shot-2022-07-19-at-14-02-46-2x.png)](https://postimg.cc/BX8BgHNR)

#### Alfred Keyboard Snippets Setup
[![Alfred's Keyboard Snippets Setup Screen](https://i.postimg.cc/vZwkmmqX/Clean-Shot-2022-07-19-at-13-58-49-2x.png)](https://postimg.cc/TpQC7TXW)

### Raindrop
My favorite bookmark manager. I use the Raindrop searchbar to quickly open links to my Github projects, work-related Sharepoint pages, Google Drive folders, and more. Raindrop is an [Alfred Workflow](https://github.com/westerlind/alfred-raindrop-search/releases).

[![Raindrop.io Searchbar](https://i.postimg.cc/k4WtqfBT/Clean-Shot-2022-07-19-at-13-55-17-2x.png)](https://postimg.cc/BLQvC55F)

## Other Applications
A list of other applications with keyboard shortcuts. This includes easy access to entering items in my Calendar, adding items to my reminders/to do list, opening a terminal window, accessing my password vault, and more.

### 1Password
My favorite password manager. I use [1Password](https://1password.com/) to save important information including my glasses prescription, ID cards, healthcare cards, passports, software IDs, and passwords.

The [1Password](https://1password.com/) search bar lets me quickly open and login to a website with just a few keystrokes. 1Password can even be used as a 2fa authenticator app, and auto-fill the code into your browser of choice (I suggest [Firefox](https://www.mozilla.org/en-US/firefox/new/)). 

The 1Password search bar is displayed when I press <kbd>⌥ Option</kbd> + <kbd>Space</kbd>

[![1Password Searchbar](https://i.postimg.cc/13S7QjXj/Clean-Shot-2022-07-19-at-13-53-11-2x.png)](https://postimg.cc/Vd7W94jq)

#### 1Password Keyboard Shortcut Setup
[![Clean-Shot-2022-07-19-at-21-53-09-2x.png](https://i.postimg.cc/44qWtRqM/Clean-Shot-2022-07-19-at-21-53-09-2x.png)](https://postimg.cc/vD77FkQL)

### Karabiner
[Karabiner Elements](https://karabiner-elements.pqrs.org/) - Optional. A *free* powerful keyboard customizer, used to remap "Capslock" to:

<kbd> Hyper (⌃ CTRL + ⌥ Option + ⌘ Command)</kbd> with any other key, or <kbd>Esc</kbd> when pressed alone. 

#### Karabiner Setup
[![Karabiner Demo](https://i.postimg.cc/bvJfFjgP/Clean-Shot-2022-07-19-at-22-21-01.gif)](https://postimg.cc/nX6WCgNS)
You can automatically import my Karabiner profile by placing /.config/karabiner in your ~/ path.

### iTerm2
* [iTerm2](https://iterm2.com/) - Great Terminal alternative with extra features like split pane. I have iTerm2 automatically appear when I type:

<kbd>⌥ Option </kbd> + <kbd>⏎ Esc</kbd>

[![iTerm is pretty](https://i.postimg.cc/ncJvZSBN/Clean-Shot-2022-07-19-at-21-18-10-2x.png)](https://postimg.cc/K40KDN95)

#### iTerm2 Keyboard Shortcut Setup
[![iterm2 keyboard shortcut settting](https://i.postimg.cc/qqQzXwqv/Clean-Shot-2022-07-19-at-21-10-55-2x.png)](https://postimg.cc/5QY4fw8h)

### Fantastical
[Fantastical](https://flexibits.com/fantastical) is a great *free* calendar app that integrates with Google, iCloud, Outlook, and more. Using neutral text language entry, users can enter items easily.

Fantastical even has an [iOS](https://apps.apple.com/us/app/fantastical-calendar/id718043190) version with great customizable homescreen widgets.

I have Fantastical calendar entry automatically appear when I type:

> <kbd>⌥ Option </kbd> + <kbd>⏎ Esc</kbd>

### Cleanshot
[![cleanshot.png](https://i.postimg.cc/gjLq44nd/cleanshot.png)](https://postimg.cc/QKsTdQQn)
[CleanShot X](https://cleanshot.com/) is a great screenshot capturing app - I used it to create this guide! CleanShot X lets you capture, edit, and annotate sceenshots and record videos & GIFs. My screenshots are captured with:

<kbd> ⇪ Capslock/Hyper (AKA ⌃ CTRL + ⌥ Option + ⌘ Command)</kbd> + <kbd> 1 </kbd>

#### Cleanshot Keyboard Shortcut Setup
[![CleanShot Keyboard Shortcuts Setup Image](https://i.postimg.cc/qR3z5FXm/Clean-Shot-2022-07-19-at-23-14-27-2x.png)](https://postimg.cc/ZBJb9VQ3)

## Trackpad Gestures
For Trackpad gestures, I use [BetterTouchTool](https://folivora.ai/). BTT lets you create gestures and keyboard shortcuts on a global and per-app basis, allowing flexibility.

### Browser Gestures

When I am working in a web browser, the following trackpad gestures allow me to...

```
Three Finger Swipe Right - Navigate to right tab
Three Finger Swipe Left - Navigate to left tab
Three Finger Swipe Down - Close active tab
Three Finger Swipe Up - Open new tab
```

<p align="center">
  <img src="https://i.postimg.cc/FzvX754k/Clean-Shot-2022-07-19-at-15-08-57.gif">
</p>

#### BetterTouchTool's Trackpad Configuration

[![BetterTouchTool's Trackpade Configuration Screen](https://i.postimg.cc/J4JxnV2Q/Clean-Shot-2022-07-19-at-14-25-24-2x.png)](https://postimg.cc/vcYfqjM1)

### Finder Gestures
I apply the same swiping gestures in Finder, the following trackpad gestures allow me to...

```
Three Finger Swipe Right - Navigate to right finder tab
Three Finger Swipe Left - Navigate to left finder tab
Three Finger Swipe Down - Close active finder tab
Three Finger Swipe Up - Open new finder tab
```

<p align="center">
<img src="https://i.postimg.cc/RCgMphQW/Clean-Shot-2022-07-19-at-14-56-36.gif">
</p>

## Hire Me
Do you think I would be a valuable asset to your software development team? I am currently open to employment - e-mail me at me@corbet.dev! 

## Special Thanks
[Nikita Noloboev's my-mac-os](https://github.com/nikitavoloboev/my-mac-os) - Inspired me to document most of my digital garden. Thanks Nikita!
[Capslock](https://github.com/Vonng/Capslock) - Inspired me to modify my capslock key.
