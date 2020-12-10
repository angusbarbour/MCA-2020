# __MCA 2020__
 ## _Week 1_ 
The central theme surrounding my MCA project will be the work of composer Claude Debussy.


Lots of data regarding Debussy's work has been manifested by many organisations and curators. The Digital Resources of Musicology have curated some notated data in the form Debussys old sheet music, the exact manuscripts of some of his music scores. The DRM also provide some minute descriptive meta data on the pieces such as NAME, DATE and Version. 
Other datasets such as the Live Music Archive have curated some accoustic data of Debussy's music being played. This data is presented via waveforms and audio and is visable and audible to the viewer. The audio has been presented alongside some basic descriptive metadata that tells us the Title, band, genre, length and more. 

## _Week 2_ 
This week I had decide on what piece of music I was going to transcribe for my project. I decided on a piece from Claude Debussy's Suite Bergamasque: Passepied. I was able to locate a scan in of the orginal sheet music arranged for piana by Debussy himself. I found this via the IMSLP music database, the link to the database can be found [here](https://imslp.org/wiki/Category:Debussy,_Claude).

For this weeks activity I was required to transcribe 10 bars from this sheet music, the PDF document of the original score can be found [here.](https://github.com/angusbarbour/MCA-2020/blob/master/suite_bergamasque.pdf).

My 10 bar transcription can be viewed below:
![transcirption](https://github.com/angusbarbour/MCA-2020/blob/master/images/Passepied_image.JPG).

## _Week 3_
__Task one:__
For this weeks task I was required to take the score that I created last week, and convert it into two different formats: musicxml and mei. I achieved the musicxml file by simply exporting my score from musescore as an XML file. However, to obtain the mei file I had to use Verovio in order to get this format. Both of my files can be seen down below:

* [mei file](https://github.com/angusbarbour/MCA-2020/blob/master/data/Passepied_redo.mei)
* [Musicxml file](https://github.com/angusbarbour/MCA-2020/blob/master/data/Passepied.musicxml)

__Task two:__ For the second task, I was to successful render my MEI file using the Verovio app. I was able to do this and the rendered vervio file can be found [here](https://angusbarbour.github.io/MCA-2020/verovio.html)


## _Week 4_
This week I was given the task of generating a JSymbolic, and using it to extract some intersting features relevant to my song. I have listed the JSymbolic extracted features below:
* Number of Pitches: 23
* Number of Pitch Classes: 8
* Range: 36
* Strong Tonal Centres: 2
* Mean Pitch: 58
* Mean Pitch Class: 5.445
* Most Common Pitch: 49
* Most Common Pitch Class: 1
* Interval Between Most Prevelant Pitches: 5
* Pitch Variability: 9.531
* Most Common Melodic Interval: 7

I have selected a few features to be extracted that I think are interesting for my song. Passepied is a song that sounds very much like you are being taken on a journey, and I wanted to know if this had anything to do with the range in notes or the number of pitches. This is why I decided to extract range and number of pitches. Although the range is only 36, it is important to note that the JSymbolic only reported 10 bars of my piece, which may explain why the number was not as high as I had anticipated. However, for only 10 bars I would argue that 23 different pitches is relatively high. It is also to be taken into account that the first 10 bars of this song are quite repitive and follow the same pitch pattern, this may be the reason for the relatively mediocore numbers. 

__Task 2:__ 

For task 2 I was required to use the Jupiter Notebook in order to generate three things from my data: A pitch histogram, A piano roll and a pitch scatter plot. 
All three of these can be seen below:

### Pitch Hisogram
![pitch histogram](https://github.com/angusbarbour/MCA-2020/blob/master/images/Pitch%20Histogram.png)

_My pitch histogram has shown me how many times a note has been played throughout the duration of the song. This is useful to detect the most common note. My pitch histogram has shown me that the most common note during the song was close to C3. My JSymbolic told me that my mean pitch was 58. After consulting with the University of South Wales online, I found that the midi number 58 represents the note inbetween A3 and B3 on the piano. These two notes are very close to C3 on the scale, and may account for why my histogram said the most common pitch was around this area._ 

### Scatter Plot
![Pitch Scatter Plot](https://github.com/angusbarbour/MCA-2020/blob/master/images/Scatter%20Plot.png)

_The scatter plot tells me what notes are most commonly played at different note lengths. The data shown on the graff appears to be consistent with my piece of music, as the majoirty of the notes in the song are played sticcatto, and are also all quavers. This would correlate with the time/note freuqnecy shown in the graph. Not only this but we can see the most common pitch once again was a C3 followed by a D. This correlates well with the previous graph._

### Piano Roll
![Piano Roll](https://github.com/angusbarbour/MCA-2020/blob/master/images/Piano%20Roll.png)

_A piano roll is used to represent what notes are played by the piano player, at what time and for how long. The data seems to be accurate as we can see the prevelance of the C3 note, as well as a lot of short notes being represented. These would account for the quavers._


## _Week 5_

For week 5, I was asked if I had 1000 mei files, what metadata elements would be most important in order to ogranise this music database. Below I have stated which metadata elements I believe are the most important for describing and organisaing music:

### Metadata regarding song.

* Title - The name given to a song by its creator.
* Composer - Who is responible for composing the song, more prevelant with orchestral and classical music than more modern day genres.
* Artist - The person who is resonsible for creating the song.
* Album - The name of the album that the song is a part of.
* Length - The length of time that the song plays for.
* File size - The physical size of the file.
* Genre - Describes what type of music the song falls under. Could be classical/rock/punk etc.
* Publisher - The name of the person or organisation that published the piece of music.
* Publisher Location - The location of where the person or organisation published the piece.
* Date of Publishing - The date of when the piece of music was actually published.
* Copyright - The restrictions put in place by the publisher to protect the song.

### Metadata regarding encoded piece.

* Encoder - The person who is responsible for encoding the piece.
* Date of Encoding - The date of when the ecoding of the document was completed.
* Location of Encoding - The location of where this person encoded the document.

### Task 2

For the second task, I was required to update my orginal MEI files header to implement some of these metadata elements into my file. This was done so that it would be easier to find and organise my piece. The updated file for this weeks work can be found [Here](https://github.com/angusbarbour/MCA-2020/blob/master/data/Passepied_redo.mei)

## _Week 7_

For week 7 I was asked to review my metadata i had previously added to my MEI file and add some more that I thoguht were important. One thing I focused on this week was adding authorisation to my data. This came in the form of adding authURI tags to my previous metadata to show they were legimite desriptors.I also focused on adding what metadata elements I thought were important, for this reason I added more data about the inital publishing of the piece. The updated file can be found [here](https://github.com/angusbarbour/MCA-2020/blob/master/data/Passepied_redo.mei). 

### Task 2 

For task two, we were asked to add css elements to our rendered verovio piece, in order to make the metadata appear a little nicer on the screen. To find the rendered MEI file please click [here](https://angusbarbour.github.io/MCA-2020/MyMeta.html).

## _Week 8_

For week 8, I was asked to find three tracks of different genres to analyse. I was asked to identify and list the important the most important technical and non technical metadata associated with the tracks. I have listed them down below:

### Track One
* Title: Techno Dance Club
* Artist: D SMILEZ
* Album: The Fun Of Dancing
* Composer: none
* Copyright info: CC BY-NC-ND 4.0 
* Genre: Techno, Dance
* Source: Freemusicarchive.org
* File/audio format: MP3
* Number of channels: 2 
* Sample rate: 44100Hz
* Bit per second: 259453
* Duration: 4:08:908

### Track Two
* Title: Ballad of sarin
* Artist: The Everymen
* Album: Live With Therese on EFMU 10-1-12
* Composer: none
* Copyright Info: CC BY-NC-ND 3.0
* Genre: Rock, Punk.
* Source: freemusicarchive.org
* File/audio format: MP3
* Number of channels: 2
* Sample Rate: 44100Hz
* Bit per second: 256000
* Duration: 1:36.357

### Track Three
* Title: Dance of the Sugar Plum Fairy
* Artist: Kevin Macleod
* Album: Classic Sampler
* Composer: P. I. Tchaikovsky
* Copyright Info: CC BY 3.0
* Genre: Classical
* Source: freemusicarchive.org
* File/audio format: MP3
* Number of channels: 2
* Sample Rate: 44100Hz
* Bit per second: 320000
* Duration: 1:59.89


## _Week 9_

## _Week 10_ 



