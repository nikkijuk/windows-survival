# Windows survival

I did migrate from OSX to Windows 10 - as I did years ago from Windows XP to OSX - but now it feels painful.

In addition I have used several years RHEL at work and know that OS can just work. Nothing fancy, but stable.

Let's see how long I manage with my XPS 15 before I format whole Win 10 over and install Linux.

# Installations take ages? 

Use package manager

http://scoop.sh/

install scoop in PowerShell

```
PS C:\Users\nikkijuk> iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

After that it goes like this 

```
PS C:\Users\nikkijuk> scoop install gradle@4.3.1
```

# Where is Bash?

Install WLS (windows linux subsystem)

# Mail? Don't nail yourself to Windows mail

Add extras buckt to scoop

```
PS C:\Users\nikkijuk> scoop bucket add extras

```

And so goes it

```
PS C:\Users\nikkijuk> scoop install thunderbird
```


```
PS C:\Users\nikkijuk> scoop install thunderbird
```
