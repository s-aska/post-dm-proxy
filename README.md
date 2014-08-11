Post Direct Message Proxy
=============

Simple proxy to Direct Message on Twitter.

#### Heroku Button

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Usage

```shell
curl -d 'status=Your Message' http://localhost:5000/
```

### for Instant noodle

```shell
echo "curl -d 'status=ippei was completed.' http://localhost:5000/" | at "+2 minutes"
```

How to use the `at` in OS X

```shell
sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.atrun.plist
```
