# handWriting_data_generator
1. Go to https://github.com/emreaksan/deepwriting and download the training and validation data
2. Alter the two filenames at the beginning on the ipnyb
3. Decide whether you want to interpolate all sequences to be the same length. If so, choose this length.
4. Run script

The script will generate sequences of images [seq_len, image_size, image_size] for single-stroke characters.

These are exported into a pickle file.

The script has been designed to only handle single-stroke characters in order to avoid discontinuities for a particular project's requirements.

There are roughly 84,000 sequences in the resulting pickle file. See the sample for an example towards the end of a sequence for the letter 'l'.

