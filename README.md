# music-classification
Classifying audio signal using Neural Networks and Manifold Learning.
The main idea is to be able to classify the audio signal to some defined groups. We can use genre as the group that describes songs that have something similar with each other.

Main project info:
[Colab Notebook](https://colab.research.google.com/drive/1bW5Cc0u95hUsf-ZLNq3Uqw6AtDFSjQri) or you can look through
[the code in GitHub](mm.ipynb).

Trying to apply window approach (i.e. split the audio into a few parts by 4-5 secs):
[Colab Notebook](https://colab.research.google.com/drive/1UWouR5xBj4PWSDoMBy1bWbR0aVNhgmRi) or you can look through
[the code in GitHub](mm_window.ipynb).

Trying to improve the feature extraction and give the model more and new info about the song (increases accuracy a bit):
[Colab Notebook](https://colab.research.google.com/drive/1ZJ_Z3ryyUb6p8LYIj68tYqiwccIQjy-o) or you can look through
[the code in GitHub](mm_v3+window.ipynb).

Trying to retrieve mel-scaled spectrograms from the audio and teach a convolutional network on their image representation (doesn't work at all D:):
[Colab Notebook](https://colab.research.google.com/drive/1ZJ_Z3ryyUb6p8LYIj68tYqiwccIQjy-o) or you can look through
[the code in GitHub](mm_melsp_images.ipynb).

Using implemented solution for music and songs in [the Urban Sound Classification Contest](https://datahack.analyticsvidhya.com/contest/practice-problem-urban-sound-classification/) to see if the solution can handle some other audio signals that are not related to music:
[Colab Notebook](https://colab.research.google.com/drive/18V1AhIE01UST6xUDx5A5Sd5DBhKkXJnu) or you can look through
[the code in GitHub](mm_sound_contest.ipynb).


