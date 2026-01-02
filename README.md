Golang bot

https://t.me/pavel_kbot_bot

Commands for use in tg
- /start
- /start hello



Commands used in project to create bot from scratch

go mod init kbot                             

go install github.com/spf13/cobra-cli@latest

cobra-cli init     

cobra-cli add version

go run main.go help                         

cobra-cli add kbot   

go build -ldflags "-X kbot/cmd.appVersion=v1.0.0"   

./kbot version                                   

