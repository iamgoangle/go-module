# :man_firefighter: GO-MODULE

#### We don't need create the project inside $GOPATH anymore...

1. Create your workspace `$ mkdir -p go-mod`

2. `$ go mod init hello` for create new hello module.

3. Add example package to `go.mod` by adding `require github.com/sirupsen/logrus v1.1.1`.

4. Create `main.go`

5. Build the project `go build`

6. You will see the log like this.

7. ```
   go: finding github.com/sirupsen/logrus v1.1.1
   go: finding github.com/davecgh/go-spew v1.1.1
   go: finding github.com/stretchr/testify v1.2.2
   go: finding github.com/pmezard/go-difflib v1.0.0
   go: finding github.com/konsorten/go-windows-terminal-sequences v0.0.0-20180402223658-b729f2633dfe
   go: finding golang.org/x/sys v0.0.0-20180905080454-ebe1bf3edb33
   go: finding golang.org/x/crypto v0.0.0-20180904163835-0709b304e793
   go: downloading github.com/sirupsen/logrus v1.1.1
   go: downloading golang.org/x/crypto v0.0.0-20180904163835-0709b304e793
   go: downloading golang.org/x/sys v0.0.0-20180905080454-ebe1bf3edb33
   ```

8. ./hello

## Where is the dependency will be kept?

In your $GOPATH.
