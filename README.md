# ijkplayer Library

Recompile the project [【bilibili/ijkplayer】](https://github.com/bilibili/ijkplayer) support RTSP.

### Import

Add it in your root `build.gradle` at the end of repositories:
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}

dependencies {

    implementation 'tv.danmaku.ijk.media:ijkplayer-java:0.8.8'
    implementation 'com.github.kevinvane:libIjkplayerAndroid:1.0.0'
}
```

