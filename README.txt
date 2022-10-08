== Just one octave up ==

This plugin adds an octaved signal to the original input signal by repeating and inverting each half wave of the input signal.
Using this approach the latency can be kept minimal while at the same time maintaining an excellent output signal quality.

This approach cannot be used to transpose a singal down or up to an arbitrary other interval.

Build:
  ./waf configure
  ./waf build
  sudo ./waf install
