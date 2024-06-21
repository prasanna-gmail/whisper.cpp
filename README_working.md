# whisper.cpp

## command to live audio trans 
```
make stream
./stream -m ./models/ggml-base.en.bin -t 8 --step 500 --length 5000
```

## issue: fatal error: 'sdl.h' file not found mac
https://github.com/deepmind/pysc2/issues/20
```
brew install sdl2
```

fixed and working.... 1 on Fri 21 Jun 2024
## command to live audio trans 
```
make stream
brew install sdl2
./stream -m ./models/ggml-base.en.bin -t 8 --step 500 --length 5000
```