# cobalt-dl
this isn't a replacement nor a alternative to https://co.wukko.me/. the script is just a cli tool to interface with the [cobalt api](https://github.com/wukko/cobalt).
### requirements
you'll need [jq](https://jqlang.github.io/jq/) and [curl](https://github.com/curl/curl). jq handles the json and curl handles the downloading of media. <br /> i will eventually replace jq with a bash only implementation.
### known problems
i haven't implemented picker types because i didn't had any use for them and the api documentation is quite mysterious about that. <br /> (ps you can probably just implement it yourself and make a pull request for that)
