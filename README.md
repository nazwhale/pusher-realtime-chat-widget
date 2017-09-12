# Realtime Chat Widget using Pusher

A Realtime Chat Widget with a Ruby backend, made with the help of this [tutorial from Pusher](http://pusher.com/tutorials/realtime_chat_widget).

### Installation Instructions

First, clone the repo and navigate to the correct directory:

```
$ git clone git@github.com:nazwhale/pusher-realtime-chat-widget.git
$ cd src/ruby-sinatra
```
Update the relevant depencencies using bundler:
```
$ bundle install
```
And run the program with the help of [Sinatra](http://www.sinatrarb.com/):
```
$ bundle exec ruby -rubygems chat.rb
```

Finally, navigate to http://localhost:4567/ to see the side-by-side example or http://localhost:4567/chat.html to see the standalone example.

Happy chatting!
