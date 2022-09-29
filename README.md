# Martha's Music Curation and Analytics


# Chapter One - 'Streaming and Schubert'

![Erlkönig](https://upload.wikimedia.org/wikipedia/commons/3/37/Erlkoenig_Schwind.jpg?20090623123544)

Based on your own experience, what do you think are some challenges to working with music and music-related data (perhaps related to access, curation, distribution, etc.)? How does your selected theme display some of these challenges? Describe the current manifestations of data relating to your selected theme, discussing how it is presently curated (collected and gathered) and how it is presented, described, and analysed.

Music is an inherently capitalised product - though considered a creative medium, the commodification of music has created an inaccessible and elitist culture by which only those with the financial means can access the truest, most valuable forms of music.

#### For example, streaming.

One can only access the 40 million plus songs on spotify by paying their fee of *just £9.99* every month to access these audio recordings. The deeper the consideration required, the greated the financial strain - Beyonce's album 'Lemonade' originally debuted on her husband Jay Z's platform, Tidal - ringing in at yet another £9.99. 

Of course, its not just the audio content that musicking peoples search for. We also seek the notations and scores of europe and america's greatest historic composers. Of course, the simplest sheet music can easily be found for free, but the harder it gets and the more the individual progresses, the more expensive, and difficult to find, the resources become.

#### So where do we stand when it comes to the public domain? Don't sites like IMSLP combat this issue?

Absolutely; IMSLP is the public battle-bot against the privitisation of culture. It still stands as one of the most difficult to use, and most essential sites for musicians, composers, analysist, curators, critics, and scholars.

#### And for my next trick I will exemplify all of these points through a _study on the music of Schubert_

Schubert (1797-1828), a 19th century romantic composer, is of course immortalised through western notation and sheet music - a very simple yet effective way of communicating sound without actually having to make any. In the 21st century we take that for granted - many musicians no longer value the skill of reading notated music, however at the time Schubert was writing the phonography cylinder hadn't been invented, let alone the LP, CD, or any semblance of digitisation. 

So historically, notation was the only way to communicate your compositions without being in the room. It took away the _need_ for composers to also fill the shoes of a director, conductor, and performer.  Now these scores hold such lesser value - the comtemporary listener can find at least 5 different excellent and professional performances of _"Erlkönig"_ on the first page of google, along with at least 5 sites offering you the sheet music on at least 5 different instruments, adapted by at least 5 more composers making his works accessible to all musicking individuals.

#### ... so the data sets?

From the view of an analytics student, his works are often curated as notational texts - often grouping several works together using opus numbers or similar, or as audio - in album or compliation formats - very different to their intended use. Yet this is the way his works are accessed most. 

Notation to sound, not notation OR sound.

# Chapter 2 - Man vs Machine: Optical Music Recognition

So we've covered why notation _used_ to be important, but what if we could take this elitist form of music language and feed it to a computer - surely if the computer could just understand what the PDF was saying, and put it into something like Musescore FOR us, that would save SO much time.

### Enter: OMR

Quick catch up on wha exactly OMR is.

OMR; Optical Music Recognition; is a new software development aimed at streaming the music notation and transcription process. You give it a PDF it tries its *very hardest* to read said PDF, and it gives you back a different file like MusicXML, or transcribing into a music notation software like Musescore.

This might sound kind of useless, since human beings don't need to see music notation in some obscure computing format - but it is. It means that musicial transcriptionists not longer need to spend hours infront of their computers writing our note for note each part of their music - they just feed the PDF to the OMR and BOOM they have a digitised version of the scanned manuscript right infront of them

#### well, in theory

The problem with OMR right now is that its not very pretty, and not very bright.

![Jennifer Coolidge - A Cinderella Story](https://i.pinimg.com/originals/9b/41/29/9b412948a8d0151d519db1cb043a9740.jpg)

Often, the OMR really struggles to read through the imperfections and humanness of the written manuscript and makes LOTS of mistakes (if it understands at all)! This can prove to actually be a very frustrating issue.

When using OMR, you have to be so meticulous about catching the mistakes - often key signatures, time signatures, accidentals, rhythm, pitch, just about everything integral to the music, gets missed by the computer. This is definitely a software in need of a LOT of training.

### So how can we use OMR to our advantage when collecting, curating, and documenting data surrounding Franz Schubert?

#### Schubert's own writing, 1815.

I took 4 different versions of the Erlkönig manuscript, gave them to Musescore's OMR and assessed the outcome.

First, I took the scan of the handwritten manuscript, potentially the original writings by Schubert himself, from 1815 and offered this to OMR.



##### Computer said no.

Unsurprisingly the OMR just didnt register the information in the PDF - the handwriting was too unique and full of inconsistencies that it just couldn't assertain any useful information from it. This is probably due to the fact that this particular OMR has not been exposed to, or 'trained in' these style of manuscript. If its difficult for me, a human being, to understand this manuscript, its going to be 100x harder for the OMR.

#### The Diabelli Print - 1826/1827

This is where music notation got a little more _high tech_. Anton Diabelli (1781-1856)


