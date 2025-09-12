Created a conda environemnt using muselsl
Using the 'classic' conda setting/compiler/library searcher

Use currectly , currently using muselsl

https://github.com/alexandrebarachant/muse-lsl

We want to stream --eeg and -ppg

muselsl stream --ppg --eeg

We also want to stream from specific type so maybe 1 type for ppg and for eeg in two different terminal windows

muselsl record --type EEG
muselsl record --type PPG
