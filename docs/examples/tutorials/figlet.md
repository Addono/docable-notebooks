

Install `figlet`. (Mac):

```bash|{type: 'command', platform: 'darwin'}
brew install figlet
```

(Linux):
```bash|{type: 'command', platform: 'linux'}
apt-get update -y
apt-get install -y figlet
```

(Windows):

```bash|{type: 'command', privileged: true, platform: 'win32'}
choco install figlet-go -y
```

`figlet` will translate the given text into an ascii banner. Try it out!

```bash|{type: 'command'}
figlet docable
```