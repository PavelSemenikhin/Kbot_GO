
go mod init kbot                             

go install github.com/spf13/cobra-cli@latest

cobra-cli init     

cobra-cli add version

go run main.go help                         

cobra-cli add kbot   

go build -ldflags "-X kbot/cmd.appVersion=v1.0.0"   

./kbot version                                   
