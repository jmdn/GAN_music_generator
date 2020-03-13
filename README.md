# GAN_music_generator
GAN designed to generate "music". The network can take in any .mp3 file to use for training. Currently, the network is only built to generate 1 second clips of music. But this can be changed. 

Use the concatenator script to concatenate all the individual .mp3 outputs that are produced during GAN during training to produce a single .mp3 that plays what the generator is learning to produce as training progresses.

Included here is an example of .mp3 output of a GAN trained on 1 second clips from the song 'Take the veil cerpin taxt" by The Mars Volta. To produce this .mp3, I saved and concatenated the output from the GAN after every 10 training epochs (~10k total training epochs in total). It's fun to listen to the GAN slowly start to learn to produce more "interesting" frequencies and dynamics as training progresses..
