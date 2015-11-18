# my-productivity-stuff
Stuff that make me more productive!

## Applications

* PyCharm
* Dash
* iTerm
* oh-my-zsh
* Sequel Pro
* TextMate
* Homebrew
* Homebrew Cask
* Alfred
* 1Password
* Chrome
* Parallels Desktop
* VOX
* 

## Websites

* [GitHub](https://github.com/)
* [stackoverflow](http://stackoverflow.com/)
* [AWS](http://aws.amazon.com/)
* 

# Open Source Projects

* Python
* Django
* [Django REST Framework](http://www.django-rest-framework.org/)
* AngularJS
* Bootstrap
* 

## Scripts

* Connect to a Cisco IPSec VPN
```osascript
  set vpn_name to "'Your VPN Name'"
  set user_name to "your username"
  set passwd to "your passwd"

  tell application "System Events"
    set rc to do shell script "scutil --nc status " & vpn_name
    if rc starts with "Connected" then
        do shell script "scutil --nc stop " & vpn_name
    else
        do shell script "scutil --nc start " & vpn_name & " --user " & user_name
        delay 2
        keystroke passwd
        keystroke return
    end if
  end tell
```

*

## My Stuffs

* [oh-my-stars](https://github.com/wolfg1969/oh-my-stars) - Search my GitHub stars locally (even with Alfre).
* 
 


