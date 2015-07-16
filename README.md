# go

gopath 설정 

mkdir -p go/src/hello
vi go/src/hello/hello.go

```
package main

import (
  "fmt"
)

func main() {
  fmt.Printf("good")
}

```
save 

### gopath 설정 
`
export GOPATH=`pwd`
`

### go install hello
go install hello
bin/hello을 실행한다. 
