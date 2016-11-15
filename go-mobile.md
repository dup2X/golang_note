```
go get golang.org/x/mobile/cmd/gomobile
gomobile init
go get -d golang.org/x/mobile/example/basic
gomobile build -target=android golang.org/x/mobile/example/basic
gomobile install golang.org/x/mobile/example/basic
```
