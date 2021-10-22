go mod init github.com/wallacemachado/estudos-graphql

## gerar esqueleto automaticamente, após criar o schema
go get github.com/99designs/gqlgen

go run github.com/99designs/gqlgen init

## rodar

go run ./server.go