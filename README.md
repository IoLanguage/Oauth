# Oauth 
An object for calculating Oauth hashes. Each hash calculation should instantiate its own Oauth instance.

Example:
```Io
digest := Oauth clone
digest appendSeq("this is a message")
out := digest OauthString
```

# Installation
`OpenSSL` should be installed and foundable in your system. Then:
```
eerie install https://github.com/IoLanguage/Oauth.git
```
