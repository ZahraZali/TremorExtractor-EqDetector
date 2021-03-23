This project is created to share a novelty method for tremor signal extraction from the seismic waveform and transient signal (e.g. earthquake) detection. It is especially useful for volcano seismology researches.

There are two folders in the project as below: 

1- The "Harmonic tremor extraction" folder contains Python codes for extracting tremor signal from the seismic waveform with the respective phase information. Also there is a one-day seismic waveform of the Holuhraun 2014-2015 eruption in Iceland (FLUR station from network 7Z (White, R. 2010)) and the results of applying the extraction process to this day. The first outputs is a figure of the spectrogram of the seismic waveform, the tremor and the transient spectrogram. The second output is an extracted harmonic tremor mseed file.
2- The "Transient signal detection" folder contains Python codes for:
- Transient signal detection.
- Detecting and timing earthquakes using the created characteristic function. The results of applying these algorithm to our one-day example are presented which are a marker file of detected earthquakes and a marker file of P-arrivals.