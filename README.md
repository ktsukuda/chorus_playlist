# Chorus-Playlist: Exploring the Impact of Listening to Only Choruses in a Playlist

This repository provides our dataset from the paper **Chorus-Playlist: Exploring the Impact of Listening to Only Choruses in a Playlist**, accepted at [the 24th conference of the International Society for Music Information Retrieval (ISMIR 2023)](https://ismir2023.ismir.net/).

The dataset consists of 7 tab-separated value (TSV) files that are contained in the "dataset" folder.
It includes the participants' responses other than the free responses.
Below, we define the columns in each TSV file and describe how to generate the figures and tables in our paper from these files.
The figure and table numbers refer to those in the paper.

## 1. participants.tsv

Columns: Participant_id, Gender, Age

## 2. preferred_playback_option_combination.tsv

Columns: Participant_id, TimePreChorus, Crossfade, TimeChorus

The most preferred option combination for the participant.
The definitions of "TimePreChorus," "Crossfade," and "TimeChorus" are given in section 4.1 of our paper.

## 3. each_option_preference.tsv

Columns: Participant_id, Choice, Option, Preference

The participant's preference for the option.

## 4. playlist_listening_willingness.tsv

Columns: Participant_id, Willingness for self-made playlists, Willingness for others' playlists

The willingness to listen to self-made playlists and others' playlists with chorus-playlist.
The definitions of self-made playlists and others' playlists are given in section 5.2 of our paper.

## 5. playlist_creation_willingness.tsv

Columns: Participant_id, Willingness for creation

The willingness to create a playlist on the premise of continuous listening to only the choruses in the playlist's songs.

## 6. property_importance_for_playlist_creation.tsv

Columns: Participant_id, Playlist type, Property, Importance

The importance of each property in creating a chorus-playlist and in creating a usual playlist.
The definitions of the properties such as SongHit and SongNew are given in section 6.1 of our paper.

## 7. playback_method_comparison.tsv

Columns: Participant_id, Playback method, Willingness

The willingness to listen to self-made playlists with each of the three playback methods: chorus-playlist, head-playlist, and 30sec-playlist.
The definitions of head-playlist and 30sec-playlist are given in section 7.1 of our paper.

## Reproduction of our results

* Table 1 was generated from preferred_playback_option_combination.tsv.
* Figure 2 was generated from each_option_preference.tsv.
* Figure 3 was generated from playlist_listening_willingness.tsv.
* Figure 4 was generated from playlist_creation_willingness.tsv.
* Figure 5 was generated from property_importance_for_playlist_creation.tsv.
* Figure 6 was generated from playback_method_comparison.tsv.

## Citation

Please cite our paper if you use this dataset in your own work:

```txt
@inproceedings{tsukuda2023chorus-playlist,
  author    = {Kosetsu Tsukuda and Masahiro Hamasaki and Masataka Goto},
  title     = {Chorus-Playlist: Exploring the Impact of Listening to Only Choruses in a Playlist},
  booktitle = {Proceedings of the 24th conference of the International Society for Music Information Retrieval},
  series    = {ISMIR 2023},
  pages     = {--},
  year      = {2023},
  doi       = {}
}
```
