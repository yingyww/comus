
# Computational Musicology -- Zoe Wong

In this course, I propose a computational analysis of my personal playlist on Spotify. My pocket playlist comprises disco, dance-pop, and sentimental ballads, which I have been accumulating since November 2020. The collection of these songs is solely influenced by my YouTube explore and radio shows. The size of my corpus is around 90 songs in the playlist from various genres, such as Korean, English, Mandarin, Cantonese, Taiwanese, and Japanese. The diversity of my favourites is inspirational to my project and I hope to understand the mechanism behind my choice.

The analysis would be conducted according to the geographical region/verbal language of the playlist: **United States (English), Korea (Korean), Hong Kong (Cantonese), Taiwan (Mandarin/Taiwanese) and Japan (Japanese)**. Each region has its distinctive features, such as: **danceability, acousticness, valence and tempo**; however, each connects each with the combination of its genre and languages, and this project aims to evaluate their similarities and patterns. Thus, in each category, both typical and unique tracks are selected, to represent or emphasize their typicality/atypicality.

*P.S. The written words of Cantonese, Mandarin and Taiwanese are all based on Chinese, in different accents.*






## Typical tracks:

**TWICE “I CAN’T STOP ME”**
It is an inclusive track with a common genre of retro and dance-pop, and Korean Pop. The catchy melodies and modern pop conclude the typical genre of my playlist.

**KYLIE MINOGUE, DUA LIPA “REAL GROOVE”**
The elements of its funk bass and disco-pop frequently appear on my playlist as an English pop. 

**Kay Tse “囍帖街 (The Wedding Invitations Streets)”**
It represents another genre of the sentimental ballad, with a slow tempo and storytelling tones. 


## Atypical tracks:

**Official HIGE DANdism “I Love…”**
It is one of the few Japanese songs in my playlist, and its genre belongs to its rock music.

**Olivia Ong “Fly Me to the moon”**
It is the only ballad song in English on my playlist.

**Mirror “Ignited”**
It is an exclusive electronic and dance-pop music in Cantonese.



# Language as genre

*Table 1: Danceability distribution in different languages*
![language_danceability](https://user-images.githubusercontent.com/99733797/156937439-879ae119-58aa-48f7-a930-052ad7cf20fc.png)

English has the highest medium of danceability among all genres, followed by Korean. Both Cantonese and Taiwanese have the even distribution of danceability between 0.4 and 0.8. Mandarin and Japanese have the lower medium of danceability among all genres. Overall, all tracks are higher than 0.5, which symbolizes my tendency in listening music with high dancebility

*Table 2: Tempo distribution in different languages*
![language_tempo](https://user-images.githubusercontent.com/99733797/156937660-064b81ac-cf2a-4302-b588-e37087b6327b.png)

Vice versa, the distribution in tempo shows an opposite pattern comparing to danceability, where English has the lowest medium, *exluding atypical tracks: Starboy, Blinding Lights (The Weeknd) and Stay (The Kid Laroi ft. Justin Bieber)*. Along with Cantonese, both distribution are the narrowest between 100 and 130 BPM. Japanese and Taiwanese have the highest medium of tempo at 150 BPM. Overall, most of the medium of tempo distribution locate around 125 BPM.


# Chromagram 

*Table 3: Chromagram of "Blinding Light" (The Weeknd)* planning to cut the x-axis for clearer insight
![chromagram_blindinglight](https://user-images.githubusercontent.com/99733797/156939165-004055a3-0b49-483c-a208-244fbf694307.png)

*Table 4: Chromagram of "In Your Eyes" (The Weeknd)* planning to cut the x-axis for clearer insight
![chromagram_inyoureyes](https://user-images.githubusercontent.com/99733797/156939167-31192d59-458c-4c0c-b424-9e9a2865e242.png)

Both tracks are part of the album "After Hours" by The Weeknd. 

From *table 3*, we can see that F chord has a consistent pattern of its timbre feature in "Blinding Light". We might hardly recognize the chorus on the chromagram; however tracing back to the track, a strong rhythmic echo in F chord clearly stands out as the bass of the song. We can also see a cycle throughout the entire song, where F chord goes to C, then C# and keep circulating. 

From *table 4*, the euclidean timbre features show the route of the bass, from G to C to F and back to G. It is relatively obvious compared to above, with many sudden change between chords, and it is not the chorus but the bass of the track. By comparing these 2 songs from the same artist, we can see that C and F chords often appear as the key timbre. 

# Self-Similarity Matrix of "Blinding Light"

*table 5: Pitch of "Blinding Light" (The Weeknd)*
![blindinglight_pitcheuc](https://user-images.githubusercontent.com/99733797/156946391-83247296-6295-4775-8318-a99fcad82200.png)

*table 6: Timbre of "Blinding Light" (The Weeknd)*
![blindinglight_timbreman](https://user-images.githubusercontent.com/99733797/156946393-de47f5ea-72e6-4716-a887-da94f5b356ae.png)

From *table 5*, we can see that the pitch class of "Blinding Light" are consistent throughout the track. If we zoom into the section from 50 secs to around 90 secs, 110 secs to around 190 secs, the patterns are identicial, referring to the chorus of track. 

From *table 6*, the sections (10-25 secs, 80-90 secs, 140-150 secs, 160-180 secs) in dark blue represents the chorus with solely instrumental music. Comparing to *table 5*, the dark blue area emphasizes the chorus without human voices. Between 100-135 sec, a small diagonal line symbolizes the repetition of section between 50-75 sec, that we could identify as the verse and pre-chorus.

"Blinding Light" thus could be divided as two divisions (verse+pre-chorus [A] and chorus [B]), and its pattern is 'BABABB'.





