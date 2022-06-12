# denoising

The Algorithm performs denoising by using a frequency noise gate.
(I got inspired by the method used in sox, e.g. "sox in.wav -n trim 0 1.5 noiseprof in.noise-profile & sox in.wav out.wav noisered in.noise-profile 0.3")

# How to Build

refer to Makefile, src/ and inc/

# How to run

./bin/denoise in.wav out.wav <threshold - default 100> <attenuation - default 0.03>
