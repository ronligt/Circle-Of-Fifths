# Circle Of Fifths

Circle of fifths with degrees, modes and chord-finder written in LaTeX and TikZ.

![example](example.png)

*Example*

You can use the file [circle_of_fifths.tex](circle_of_fifths.tex) to create three PDF's, print, cut out (, laminate) and join them in the center:

![photo](photo.png)

*(older version)*

## Instruction

In the LaTeX document look for the `Phase` comments and follow the instructions. Print after each phase. The document is set default to the first phase.

Note that in the 'degree'-layer you need to cut out the parts where it says `cut out`...

If you cannot create the PDF's please download the [base.pdf](base.pdf), [degree.pdf](degree.pdf) and [chords.pdf](chords.pdf).

You can try to join the three pieces in the center with a [split pin](https://en.wikipedia.org/wiki/Brass_fastener).

## Description

**nomenclature:**
* *tonic*: the root or home note of a key
* *key* and *scale*: the order of notes determined by the tonic. For the purpose of this text key and scale are similar. Although: "A scale is musical notes arranged in an order, whereas a key is determined by the tonic note from which we derive the chords of a scale. A mode is an elaboration of a scale." (from <https://www.musicianwave.com/key-vs-scale-vs-mode/>)
* *degree*: the position of a particular note on a scale relative to the tonic (from <https://en.wikipedia.org/wiki/Degree_(music)>)
* *mode*: a scale of notes within one key starting at a certain note within that key, each mode with its own "characteristic melodic and harmonic behavior" (loosely from <https://en.wikipedia.org/wiki/Mode_(music)>)

![description](description.png)

The upper ring on the base plate shows the root note (*tonic*) of the major keys **`[green ring]`** in the circle of fifths, below this note is the number of &flat; or &sharp; in that key **`[yellow ring]`** and below that the parallel minor tonic **`[red ring]`** (e.g. A- is the parallel minor of C).

The middle ring shows the seven degrees (scale step) in a key from **I&xutri;** to **vii&oslash;** **`[blue ring]`**. These consist of a roman number and a **&xutri;**, a **7** or a **&oslash;**. An upper roman number indicates a major chord (major third) and a lower roman number a minor chord (minor third). The **&xutri;** indicates a major seventh chord, the **7** a minor seventh chord and the **&oslash;** a half-diminished seventh chord (minor third, diminished fifth and minor seventh). Below the modes in some cases the odd note numbers above the octave are shown: the 9th, 11th and 13th as they are often used as extensions of a chord **`[orange ring]`**. Below that the names of the modes corresponding with the degree from **ionian** to **locrian** **`[blue text]`**. Below the **ionian** and **aeolian** it shows the common names **major** and **natural minor** **`[red text]`**.

The inner disc show the notes in a chord in the holes on the disc together with their note numbers. The chord is selected with the arrow on the disc (see [Usage](#usage) for more information).

## Usage

1. Turn the middle ring (the degrees) with the **I&xutri;** (*ionian*) pointing to the tonic of your major key in the upper ring (closest to the edge, in the example above pointing to C).

   ![find major root](step_1_major.png)

   For the minor key point the  **vi7** (*aeolian*) to the tonic of your minor key in the upper ring (again closest the edge, in the example above pointing to A).

   ![find minor root](step_1_minor.png).
1. Rotate the arrow on the inner disc to point to the desired chord (=degree) on the middle ring.

   ![find chord](step_2.png)
1. On the inner disc you find the notes of that chord in the selected key (in the example on top: C-E-G-B).

   ![find notes](step_3.png)

   Note that for the seventh degree **vii&oslash;** you will need to add the upper note indicted in the slice with "add to vii&oslash; (5)".

### Find the scale

Disclaimer: the author of this text is an amateur musician at best and his theoretical knowledge is very basic. The following tips are from his own experience and have not been checked by a professional musician.

There are several steps that might help to figure out the tonic and the key of a piece of music:

1. how many &flat; or &sharp; are written at the start of the piece? In the upper ring you can find the corresponding major or minor key
1. what is the last chord of the piece? More than often a piece of music ends with the root chord (chord starting with the tonic of the key)or tonic
1. what is the first chord of the piece? Also often a piece of musics starts with the root chord
1. check the chords in the piece and rotate the middle ring with the degrees until it fits (most) of these chords (pay attention to major/minor and seventh). At the first degree (**I&xutri;**) you will find the tonic of the major key in the upper ring and at the sixth degree (**vi7**) you will find the tonic of the minor key in the upper ring

Is the piece major or minor?

1. listen to the music! Although this being a grave oversimplification a minor song tends more towards a 'sad' emotion whereas a major songs gives you a more 'happy' feeling
1. again the last chord of the piece. If this is the root chord the chord itself will tell you if the key is major or minor
1. this will also uphold if the first chord of the piece is the root chord

### Read a chord

Chords are typically a combination of three or more notes. Each chord has a name indicating the root note of the chord together with added letters, numbers and symbols to specify all the other notes in the chord. An example of a chord can be **C7**:

* The **C** indicates the root note of the chord
* The C-chord consists of three notes: the tonic, the major third (four semitones from tonic) and the perfect fifth (seven semitones from tonic)
* The **7** indicates the addition of the **minor** seventh (ten semitones from tonic)

The resulting notes of this chord are:

* C *tonic*
* E *major third*
* G *perfect fifth*
* B&flat; *minor seventh*

Sometimes you see the following notation: **D/E**. This is called *D over E* (or *slash chord*). The chord is **D** and the bass note is the **E** and not the tonic of D scale (being D).

Below is a list of symbols that can be used:

| symbol | name | meaning | semitones from tonic
| :---: | --- | --- | :---:
| - | *minor third* | | 3
| m | *minor third* | | 3
| &xutri; | *major seventh* | | 11
| Maj7 or Maj or M7 or M | *major seventh* | | 11
| &flat;5 | *diminished fifth* | also with other notes | 6
| &oslash; | *half diminished* or *half dim* | *tonic* - *minor third* - *diminished fifth* -  *minor seventh* | 0 - 3 - 6 - 10
| o or dim | *diminished* | *tonic* - *minor third* - *diminished fifth* -  *diminished seventh* | 0 - 3 - 6 - 9
| + | *augmented fifth* | | 8
| aug | *augmented fifth* | | 8
| &sharp;5 | *augmented fifth* | also with other notes | 8
| sus or sus4 | *perfect fourth* | instead of third | 5
| sus2 | *major second* | instead of third | 2
| 6 | *major sixth* | instead of fifth | 9
| 9 | *major ninth* | mostly implies 7 | 14
| 11 | *perfect eleventh* | mostly implies 7 | 17
| 13 | *major thirteenth* | mostly implies 7 | 21
| 6/9 or 6add9 | *six nine* | 6 instead of 5 and 9 instead of 7 | 0 - 3 - 9 - 14

## Acknowledgement

*Many thanks to Joel Mabus for his Wheel Of Fifths <http://www.joelmabus.com/mabus%20wheel%20of%20fifths.htm> and the authors of the code found in <https://tex.stackexchange.com/questions/442783/circle-of-fifths-diagram-with-printed-music-in-latex>*
