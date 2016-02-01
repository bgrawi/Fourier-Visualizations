# [Fourier-Visualizations](http://bgrawi.com/Fourier-Visualizations/)
An HTML5 canvas visualization of how Fourier series, or adding smaller and faster sin waves together, can approximate any periodic wave that you can then hear directly. These visualizations provide the foundation for oscillators used in most music synthesizers. The visualization shows each sin wave as a circle being added to the previous sin wave's value. It color codes them so that the equation, component, and circle can be easily recognized. By using the WebAudio API, these waves can be heard individually or all together by directly using the math shown. Since we can't hear sound waves of 1-2Hz, the audio frequency is instead based at 220Hz, but the actual sound wave is still exactly what is shown (save for normalization of the > 1 values).

## Tips and things to try
* Adjust your volume then click on the speaker in the top right to hear the wave @ 220hz
* Try sliding the n slider or use your arrow keys to change how many terms there are
* Select the middle silder to hear only one term at a time, then toggle it back to hear that one frequency help form the overall wave
* Try pausing the simulation, then stepping with the S key (or the button) when theta is 0 or pi.
* Listen to how the ringing goes away when the Lanczos sigma factor is added and notice how the wave is actually louder

## To do
* Refactor out into separte files for better management
* Explore other waveforms, maybe custom ones with FFT
* Show the actual audio output oscilloscope complete with normalization and zooming

## MIT License

Copyright (c) 2016 Ben Grawi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
