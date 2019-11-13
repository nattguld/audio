# audio

## About
Allows to easily play audio files in a queued manner or just straight away.

## Examples
```java
Audio audio = new Audio(File file);
Audio audio = new Audio(String filePath);
Audio audio = new Audio(URL url);

AudioManager.submit(Audio audio); //Queued
audio.play(); //Direct
```
