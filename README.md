# demo-volatc

![](volatc.png)

To run the demo...

```bash
git clone git@github.com:engelsjk/demo-volatc.git
```

Then spin up a simple web server.

```bash
http-server
```

On the map, click an airport feed (red dot) to start streaming audio. It may take a few seconds for the audio stream to load. You can have more than one feed streaming at a time.

As you move the map around, the volume for each station will change depending on how far that station is from the center of the map (or turn off if it is out of view). Inspired by [this tweet](https://twitter.com/morganherlocker/status/1519905348995280898).

Finally, please be aware of this [information](https://www.liveatc.net/legal/).
