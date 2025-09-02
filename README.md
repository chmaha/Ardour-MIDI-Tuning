Ardour (via Lua) currently only has separate A4 pitch setting or scala-to-MIDI tuning. Unfortunately, using them in sequence overwrites the previous. The lua file provided here allows for both reference pitch and scala tuning at the same time - extremely useful for baroque keyboardists needing something like A=415 Kirnberger III.

 Tested with `a-fluidsynth.lv2` but you should be able to use with any synth that can accept MTS messages.
