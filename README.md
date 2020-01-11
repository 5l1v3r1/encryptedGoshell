# encryptedGoshell
Reverse TCP shell with network level encryption (AES cipher) written in Golang.

- Installing packages for build
```
admin@local:~$ go get github.com/gonutz/w32
admin@local:~$ go get github.com/fatih/color
```

- Building the client/server
```
admin@local:~$ set GOARCH=386
admin@local:~$ go build server.go
admin@local:~$ go build shell.go
```
