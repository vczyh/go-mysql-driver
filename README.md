## Install

```shell
go get github.com/vczyh/go-mysql-driver
```

## Usage

```go
import _ "github.com/vczyh/go-mysql-driver"

db, err := sql.Open("mysql", "mysql://root:Unicloud@1221@10.0.44.59:3306")
if err != nil {
	// handle error
}

if err := db.Ping(); err != nil { 
	// handle error
}
```