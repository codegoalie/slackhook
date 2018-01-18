[![GoDoc](https://godoc.org/github.com/videofruit/slackhook?status.png)](https://godoc.org/github.com/videofruit/slackhook)
[![Build Status](https://travis-ci.org/videofruit/slackhook.svg?branch=master)](https://travis-ci.org/videofruit/slackhook)

# slackhook

Minimal client for [Slack's](https://slack.com/) [Incoming
WebHooks](https://api.slack.com/incoming-webhooks) API.

## Examples

```go
import "github.com/videofruit/slackhook"

slackHook := slackhook.New(webhookURL, slackhook.ClientOptions{})

slackHook.Simple("Hello from slackhook!")
```
