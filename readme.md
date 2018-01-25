# Windows survival

I did migrate from OSX to Windows 10 - as I did years ago from Windows XP to OSX - but now it feels painful.

In addition I have used several years RHEL at work and know that OS can just work. Nothing fancy, but stable.

Let's see how long I manage with my XPS 15 before I format whole Win 10 over and install Linux.

## Installations take ages? 

Use package manager

http://scoop.sh/

install scoop in PowerShell

```
PS C:\Users\nikkijuk> iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

After that you can search for software

```
PS C:\Users\nikkijuk> scoop searc gradle
```

And install it (in desiered version if needed)

```
PS C:\Users\nikkijuk> scoop install gradle@4.3.1
```

## Supported suftware

Search or look directly from repository

https://github.com/lukesampson/scoop/tree/master/bucket

https://github.com/lukesampson/scoop-extras

## Where is Bash?

Guess what: there isn't one - but cool as it is - you can get it from MS.

Enable WLS (windows linux subsystem)

https://docs.microsoft.com/en-us/windows/wsl/install-win10

Install suse from windows store

https://www.microsoft.com/en-us/store/p/opensuse-leap-42/9njvjts82tjx

There's other Linux variants too - I just picked this due to recommendation from my good friend, and hope it works for me.

## Mail? Don't nail yourself to Windows mail

Add extras buckt to scoop

```
PS C:\Users\nikkijuk> scoop bucket add extras

```

Install thunderbird

```
PS C:\Users\nikkijuk> scoop install thunderbird
```

## Epub ?

``
PS C:\Users\nikkijuk> scoop install calibre-normal
```

##

Office ?

There doesn't seem to be open office or libre office package definitions for Scoop. Strange it is.

Which to choose? 

http://www.zdnet.com/article/openoffice-is-dead-long-live-libreoffice/

http://www.zdnet.com/article/apache-should-deprecate-openoffice-and-send-users-to-libreoffice-instead/

http://www.techradar.com/news/the-best-free-office-software

I have previously always taken open office, and it might continue like this. Anyway: I need to install it by hand.

## Virtual box

No scoop support - install by hand

https://www.virtualbox.org/wiki/Downloads

## Docker

https://github.com/lukesampson/scoop/wiki/Docker-and-Docker-Composex

scoop install docker
scoop install docker-machine

docker-machine create default



## 
