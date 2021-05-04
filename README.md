# datafiles
Proto files to implement grpc client and server for memdbclient and memdbserver.

### Generate code from proto files
Go to the directory where proto file reside.
For example
    cd hash
    cd stack
Run below command
```sh
    protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative <filename>
```