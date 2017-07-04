Manipulate[
 Dynamic[
  Play[
   (1 - aT*Sin[2 \[Pi]*TremFreq*x])*
    (a1*Sin[
        2 \[Pi]*1 x*ToneFreqSlider + v1*Sin[2 \[Pi]*VibrFreq*x] + 
         phase1] +
      a2*Sin[
        2 \[Pi]*2 x*ToneFreqSlider + v2*Sin[2 \[Pi]*VibrFreq*x] + 
         phase2] +
      a3*Sin[
        2 \[Pi]*3 x*ToneFreqSlider + v3*Sin[2 \[Pi]*VibrFreq*x] + 
         phase3] +
      a4*Sin[
        2 \[Pi]*4 x*ToneFreqSlider + v4*Sin[2 \[Pi]*VibrFreq*x] + 
         phase4] +
      a5*Sin[
        2 \[Pi]*5 x*ToneFreqSlider + v5*Sin[2 \[Pi]*VibrFreq*x] + 
         phase5] +
      a6*Sin[
        2 \[Pi]*6 x*ToneFreqSlider + v6*Sin[2 \[Pi]*VibrFreq*x] + 
         phase6] +
      a7*Sin[
        2 \[Pi]*7 x*ToneFreqSlider + v7*Sin[2 \[Pi]*VibrFreq*x] + 
         phase7]), 
   {x, 0, 1.}]],
 
 {{ToneFreqSlider, 220, "Tone Frequency"}, 0, 2000, 
  Appearance -> "Labeled"},
 Delimiter,
 {{a1, 1, "Harmonic Amplitude - n=1"}, 0, 2, Appearance -> "Labeled"},
 {{a2, 1, "Harmonic Amplitude - n=2"}, 0, 2, Appearance -> "Labeled"},
 {{a3, 1, "Harmonic Amplitude - n=3"}, 0, 2, Appearance -> "Labeled"},
 {{a4, 1, "Harmonic Amplitude - n=4"}, 0, 2, Appearance -> "Labeled"},
 {{a5, 1, "Harmonic Amplitude - n=5"}, 0, 2, Appearance -> "Labeled"},
 {{a6, 1, "Harmonic Amplitude - n=6"}, 0, 2, Appearance -> "Labeled"},
 {{a7, 1, "Harmonic Amplitude - n=7"}, 0, 2, Appearance -> "Labeled"},
 Delimiter,
 {{VibrFreq, 0, "Vibrato Frequency"}, 0, 10, Appearance -> "Labeled"},
 Delimiter,
 {{v1, 1, "Vibrato Amplitude - n=1"}, 0, 2, Appearance -> "Labeled"},
 {{v2, 1, "Vibrato Amplitude - n=2"}, 0, 2, Appearance -> "Labeled"},
 {{v3, 1, "Vibrato Amplitude - n=3"}, 0, 2, Appearance -> "Labeled"},
 {{v4, 1, "Vibrato Amplitude - n=4"}, 0, 2, Appearance -> "Labeled"},
 {{v5, 1, "Vibrato Amplitude - n=5"}, 0, 2, Appearance -> "Labeled"},
 {{v6, 1, "Vibrato Amplitude - n=6"}, 0, 2, Appearance -> "Labeled"},
 {{v7, 1, "Vibrato Amplitude - n=7"}, 0, 2, Appearance -> "Labeled"},
 Delimiter,
 {{aT, 0, "Tremolo Amplitude"}, 0, 1, Appearance -> "Labeled"},
 Delimiter,
 {{TremFreq, 0, "Tremolo Frequency"}, 0, 10, Appearance -> "Labeled"},
 Delimiter,
 {phase1, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase2, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase3, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase4, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase5, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase6, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"},
 {phase7, -2 \[Pi], 2 \[Pi], Appearance -> "Labeled"}
 ]