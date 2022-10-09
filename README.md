## Slack app
~~ api.slack.com/apps

bot name: age-calc-bot

in socket mode we have to create an app token

then in event subscription add some bot events...

and also in oauth add some permission by scope or API method and press install to workspace and get an OAuth token

create main.go

go mod init
if it is necessary << export GO!!!MODULE="on" >>

go mod tidy

go get "git hub packages"  << go get "github.com/shomali11/slacker" >>

go build

go run main.go


