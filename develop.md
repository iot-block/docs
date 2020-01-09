## Develop guide

### Build JS SDK

First, clone this project: [iotchain](https://github.com/iot-block/iotchain)

```
$ sbt
> project sdkJS
> fullOptJS
```

Then you can find `jbok-sdk-opt.js` in `<projectPath>/sdk/js/target/scala-2.12/scalajs-bundler/main/jbok-sdk-opt.js`, it's our sdk library.
