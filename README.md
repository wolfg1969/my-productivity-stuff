# my-productivity-stuff
Stuff that make me more productive!

## Tools

* [Alfred](https://www.alfredapp.com/)
* [PyCharm](https://www.jetbrains.com/pycharm/)
* [Dash](https://kapeli.com/dash)
* [iTerm2](https://www.iterm2.com/)
* [oh-my-zsh](http://ohmyz.sh/)
* [Sequel Pro](http://www.sequelpro.com/)
* [TextMate](https://macromates.com/)
* [Homebrew](http://brew.sh/)
* [Homebrew Cask](http://caskroom.io/)
* [1Password](https://agilebits.com/onepassword)
* [Parallels Desktop](http://www.parallels.com/cn/products/desktop/)
* [VOX Player](http://coppertino.com/vox/mac)
* 

## Websites

* [GitHub](https://github.com/)
* [stackoverflow](http://stackoverflow.com/)
* [AWS](http://aws.amazon.com/)
* 

# Programming Languages & Frameworks

* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)
* [Django REST Framework](http://www.django-rest-framework.org/)
* [AngularJS](https://angularjs.org/)
* [Bootstrap](http://getbootstrap.com/)
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

## My Stuff

* [oh-my-stars](https://github.com/wolfg1969/oh-my-stars) - Search my GitHub Stars locally (even with Alfre).
* 
 


