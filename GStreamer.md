## GStreamer
> inference:
>
> https://gstreamer.freedesktop.org/documentation/installing/index.html
>
> https://blog.csdn.net/knowledgebao/article/details/84621238
>
> https://blog.csdn.net/yanbixing123/article/details/52970956



### installing on Ubuntu

```bash
sudo apt-get install libgstreamer1.0-0 gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav gstreamer1.0-doc gstreamer1.0-tools gstreamer1.0-x gstreamer1.0-alsa gstreamer1.0-gl gstreamer1.0-gtk3 gstreamer1.0-qt5 gstreamer1.0-pulseaudio
```



### compile

add `pkg-config --cflags --libs gstreamer-1.0` to `gcc` command

```bash
# eg
gcc basic-tutorial-1.c -o basic-tutorial-1 `pkg-config --cflags --libs gstreamer-1.0`
```



