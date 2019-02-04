---
title:      "Messenger Bot Quickstart in Golang"
author:     Sirius Dely
tags:       [ golang, learning ]
---

When I want to learn something new. It is much easier for me to make something out of it. Probably because my learning type is _kinesthetic_, must involve physical muscle. In the case of learning to code, muscle involved is finger muscle while typing the code. Coding is not typing, but still ... typing is involved ... for now.

So I decided to learn Go programming language. Intrigued by its well-known good performance, and also its built-in `async`. And also, which is another big reason, being bored by _messy_ `javascript` on `nodejs`.

So before I was able to code in Golang, of course, I need to learn it a bit first, which involved reading. Here is my reading list for Golang:

1. [Golang Documentation](https://golang.org/doc)
2. [A Tour of Go](https://tour.golang.org)
3. [Writing Web Applications in Go](https://golang.org/doc/articles/wiki)
4. [Building Web Apps with Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go)
5. [Build web application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang)

After reading those above, my brain and hands start to be itchy to try the language. And because I also wanted to learn about `chatbot`, and after reading [Facebook Messenger Quick-Start](https://developers.facebook.com/docs/messenger-platform/guides/quick-start), I decided to rewrite the [messenger-bot](https://gomix.com/#!/project/messenger-bot) in Go.

And then, this is what I have come up with so far: this [go-messenger-bot](https://github.com/siriusdely/go-messenger-bot) Github repo.

Let me just paste its README.md here:

-----------------

## go-messenger-bot
Facebook Messenger Quick-Start Sample in Golang https://glitch.com/edit/#!/project/messenger-bot

### building and running

`go build messenger-bot.go`
`VERIFY_TOKEN=??? PAGE_ACCESS_TOKEN=??? ./messenger-bot`

### using docker
`docker run --publish 8080:8080 --env VERIFY_TOKEN=??? --env PAGE_ACCESS_TOKEN=??? siriusdely/go-messenger-bot`

-----------------

OK, that's it.

Point for improvements:

- Use [ngrok](https://ngrok.com) so that it can be tried live on [FB Apps](https://developers.facebook.com/apps)
- Use Go Struct on JSON parsing
- Use [Wit.ai](https://wit.ai) - probably for another blog post
- Add some images/screenshots to this post to make it more interesting.
