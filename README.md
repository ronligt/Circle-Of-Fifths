# Circle Of Fiths

Circle of fifths with modes and chord-finder written in LaTeX and TikZ.

![example](example.png)

*Example*

You can use the file [circle_of_fifths.tex](circle_of_fifths.tex) to create three PDF's, print, cut out (, laminate) and join them in the center:

![photo](photo.png)

*(older version)*

In the LaTeX document look for the `Phase` comments and follow the instructions. Print after each phase. The document is set default to the first phase.

Note in the 'modes'-layer you need to cut out the parts where it says `cut out`...

If you cannot create the PDF's please download the [base.pdf](base.pdf), [modes.pdf](modes.pdf) and [chords.pdf](chords.pdf).

## Description

The upper ring on the base plate shows the root note of the scales in the circle of fifths, below this notes is the number of &flat; or &sharp; in that scale and below that the parallel minor root note (e.g. A- is the parallel minor of C).

The middle ring shows the seven degrees (scale step) in a scale from **I&xutri;** to **vii&oslash;**. These consist of a roman number and a **&xutri;**, a **7** or a **&oslash;**. A upper roman number indicates a major chord (major third) and a lower roman number a minor chord (minor third). The **&xutri;** indicates a major seventh chord, the **7** a minor seventh chord and the **&oslash;** a half-diminished seventh chord (minor third, diminished fifth and minor seventh). Below the modes in some cases the odd note numbers above the octave are shown: the 9th, 11th and 13th as they are often used as extensions of a chord. Below that the names of the actual modes corresponding with the degree from **ionian** to **locrian**. Below the **ionian** and **aeolian** it shows the common names **major** and **natural minor**.

The inner disc show the notes in a chord in the wholes on the disc together with their note numbers. The chord is selected with the arrow on the disc (see [Usage](#usage) for more information).

## Usage

1. Turn the middle ring (the degrees) with the **I&xutri;** (*ionian*) pointing to the root note of your major scale in the upper ring (closest to the edge, in the example above pointing to C). For the minor scale point the  **vi7** (*aeolian*) to the root note of your minor scale in the upper ring (again closest the edge, in the example above pointing to A).
1. Rotate the arrow on the inner disc to point to the desired chord (=degree) on the middle ring.
1. On the inner disc you find the notes of that chord in the selected scale. Note that for the seventh degree **vii&oslash;** you will need to add the upper note indicted in the slice with "add to vii&oslash; (5)".

*Many thanks to Joel Mabus for his Wheel Of Fifths <http://www.joelmabus.com/mabus%20wheel%20of%20fifths.htm> and the authors of the code found in <https://tex.stackexchange.com/questions/442783/circle-of-fifths-diagram-with-printed-music-in-latex>*
