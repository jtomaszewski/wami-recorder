WAMI Recorder
=============

Yet another clone of [WAMI Recorder](https://code.google.com/p/wami-recorder/).

# Source recompiling

1. Download Adobe's free Flex SDK.
2. Check out the project into a directory (e.g. ~/wami-recorder) and compile it from the command line within that directory:
```bash
mxmlc -compiler.source-path=src \
  -static-link-runtime-shared-libraries=true \
  -output example/client/Wami.swf \
  src/edu/mit/csail/wami/client/Wami.mxml
```
