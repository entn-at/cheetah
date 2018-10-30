# C Demo

## Build

```bash
gcc -O3 -I../../include/ cheetah_demo.c -ldl -o cheetah_demo
```

## Running

```bash
./cheetah_demo ../../lib/linux/x86_64/libpv_cheetah.so ../../lib/common/acoustic_model.pv ../../lib/common/language_model.pv ../../resources/license/cheetah_eval_linux_public.lic ../../resources/audio_samples/test.wav
```
