Test Clips
==========

512x288 test clips.

Downsampled from lossless HD video and losslessly encoded using a command similar to:

```
ffmpeg -i in.y4m -r 25 -vf scale=512:288 -sws_flags spline+accurate_rnd+full_chroma_int+full_chroma_inp -c:v libaom-av1 -crf 0 -cpu-used 3 out.mkv
```

Acknowledgement
---------------

Most content is taken from [here](https://media.xiph.org/video/derf/)
