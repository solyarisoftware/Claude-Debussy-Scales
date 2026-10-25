# Claude Debussy's Scales

This repository contains a REAPER `.reascale` file I created, documenting the scales and pitch
collections used by composer **Claude Debussy** (1862–1918).

Debussy did not develop a single personal system, the way Scriabin did: he drew freely from
several collections, treating them as interchangeable colours in a connected harmonic network.
The file holds **22 scale entries** in five collections, each annotated with its intervals, its
modes/rotations and its notes from C — arranged from the most symmetric to the richest:

1. **Whole-tone scale** — 6 notes, 1 mode, 2 transpositions
2. **Octatonic scale** — 8 notes, 2 modes, 3 transpositions
3. **Pentatonic** — 5 notes, 5 modes, 12 transpositions
4. **Diatonic modes** — 7 notes, 7 modes, 12 transpositions (Ionian, Dorian, Phrygian, Lydian,
   Mixolydian, Aeolian, Locrian)
5. **Acoustic / Lydian dominant** — 7 notes, 7 modes, 12 transpositions

## Files Included

- **[Claude-Debussy-Scales.reascale](Claude-Debussy-Scales.reascale)** — the REAPER scale file,
  with one submenu per collection
- Scale descriptions and theoretical background below

## Debussy's Five Collections

### 1. Whole-tone scale

**Intervals:** 2-2-2-2-2-2 · 6 notes · 1 mode · 2 transpositions

Shared with Scriabin, but even more central to Debussy's identity: Messiaen, who codified it as
his *Mode 1 of Limited Transposition*, said that after Debussy there was "nothing else to add".
Without a leading tone or a dominant–tonic pull it dissolves functional tonality into a blurred,
hovering colour, and every triad built from it is augmented.

*Key works:* **Voiles** (Préludes Bk 1, 1909), almost entirely within one whole-tone scale with a
brief pentatonic contrast; *Cloches à travers les feuilles* (Images Bk 2, 1907), *La mer*, *Jeux*,
*Images* pour piano No. 1, *Pelléas et Mélisande* Act 4 sc. 2, *Prélude à l'après-midi d'un faune*
(bars 32–33 and 35–36).

### 2. Octatonic scale

**Intervals:** 1-2-1-2-1-2-1-2 (half-whole) · 2-1-2-1-2-1-2-1 (whole-half) · 2 modes · 3 transpositions

Also shared with Scriabin, but used differently: shorter passages, fluid juxtaposition with other
collections, rather than Stravinsky's structural blocks.

### 3. Pentatonic scale

**Intervals:** 2-2-3-2-3 · 5 notes · 5 modes · 12 transpositions

The most distinctly Debussy addition to the palette. He heard Javanese gamelan in the Dutch
pavilion of the 1889 Paris Exposition and returned "again and again" — his own words: *"the
Javanese music makes our tonic and dominant seem like empty phantoms for the use of unwise
infants"*. In **Pagodes** alone he uses five or six versions of the pentatonic scale, partly to
evoke the subtly out-of-tune quality of gamelan *slendro*.

*Key works:* Pagodes (Estampes, 1903) — the most thoroughgoing use; *La cathédrale engloutie*
(pentatonic mixed with modes); *Et la lune descend sur le temple qui fut* (Images Bk 2); *La mer*.

All five rotations are included, named with standard ethnomusicological terminology (Egyptian,
Man Gong, Ritusen/Yo, minor). The rotations other than the major and the minor pentatonic are
included as members of the same family: their direct attribution in Debussy is less specific.

### 4. Diatonic modes

**Intervals:** 2-2-1-2-2-2-1 (Ionian) and its six rotations · 7 notes · 7 modes · 12 transpositions

The systematic revival of the church modes. The plain major scale is present too — for lyrical
second themes and moments of tonal resolution — but it is constantly escaped from, which makes
the modal departures more vivid by contrast.

*Key works:* Ionian — *Clair de lune*, *La fille aux cheveux de lin*, *L'isle joyeuse* (second
theme in pure A major); Dorian — the opening dance theme of *Fêtes* (Nocturnes), *La cathédrale
engloutie* bars 22–27; Phrygian — the opening of *La cathédrale engloutie*, *La soirée dans
Grenade* (Estampes); Lydian — *L'isle joyeuse*; Mixolydian — *La cathédrale engloutie* bars
33–37, *Fêtes*.

### 5. Acoustic scale / Lydian dominant

**Intervals:** 2-2-2-1-2-1-2 · 7 notes · 7 modes · 12 transpositions

Shared with Scriabin, where it is the parent of the Prometheus/Mystic collection (the Prometheus
scale = the acoustic scale with the perfect fifth omitted). Its seven rotations are **identical**
to the seven modes of the ascending melodic minor: Lydian dominant, Mixolydian b6, Locrian #2,
Altered, melodic minor, Dorian b2, Lydian augmented. The name "acoustic" (Ernő Lendvai, 1955)
refers to its resemblance to partials 8–14 of the harmonic series; jazz formalized it as the
"Lydian dominant" (George Russell, 1953).

*Key works:* *L'isle joyeuse* (1904), described by Tymoczko as "involving a central acoustic
scale"; *Nuages* (Nocturnes, 1899), where the G acoustic scale appears from bar 21 as "a
compromise between the octatonic and whole-tone scales".

## The scale network (Tymoczko 2004)

Dmitri Tymoczko, in *Scale Networks and Debussy* (Journal of Music Theory 48.2, 2004), shows
that these collections form a **connected network** in which adjacent scales share a maximum of
common tones — precisely the voice-leading relationships Debussy exploited to move fluidly
between harmonic worlds. The acoustic scale acts as the mediator between the whole-tone and the
diatonic collections, just as in Scriabin it mediates between the whole-tone and the octatonic
via the Prometheus collection: a striking structural parallel between the two composers.

## Quick reference table

| # | Collection | Intervals | Notes | Modes | Transpositions |
|---|---|---|---|---|---|
| 1 | Whole-tone | 2-2-2-2-2-2 | 6 | 1 | 2 |
| 2 | Octatonic | 1-2-1-2-1-2-1-2 / 2-1-2-1-2-1-2-1 | 8 | 2 | 3 |
| 3 | Pentatonic | 2-2-3-2-3 + 4 rotations | 5 | 5 | 12 |
| 4 | Diatonic | 2-2-1-2-2-2-1 + 6 rotations | 7 | 7 | 12 |
| 5 | Acoustic | 2-2-2-1-2-1-2 + 6 rotations | 7 | 7 | 12 |

## Using the file in REAPER

Copy the `.reascale` into the `Data/` folder of your REAPER resource directory (on Windows
`%APPDATA%\REAPER\Data`) — that is the only place REAPER reads scales from — then pick it in the
**Key snap** dropdown of the MIDI editor. Note that setting a scale only greys out the notes
outside it: to make notes actually snap while you play or record, use `VST: ReaControlMIDI` (key +
scale) or `JS: MIDI Snap To Key`.

Companion repositories: [Alexander-Scriabin-Scales](https://github.com/solyarisoftware/Alexander-Scriabin-Scales)
and [Olivier-Messiaen-Modes](https://github.com/solyarisoftware/Olivier-Messiaen-Modes).

## References

- Tymoczko, D. (2004). *Scale Networks and Debussy*. Journal of Music Theory, 48(2), 219–294.
  <https://dmitri.mycpanel.princeton.edu/debussy.pdf>
- Forte, A. (1991). *Debussy and the Octatonic*. Music Analysis, 10(1–2), 125–169.
- Day-O'Connell, J. (2009). *Debussy, Pentatonicism, and the Tonal Tradition*. Music Theory
  Spectrum, 31(2), 225–261.
- Tamagawa, K. (1988). *Echoes from the East: The Javanese Gamelan and its Influence on the Music
  of Claude Debussy*. Dissertation, University of Texas, Austin.
- Bernstein, L. (1958). *What Is a Mode?* Young People's Concerts.
- Hugh, B. (2001). *Debussy and the Gamelan*. <https://brenthugh.com/debnotes/gamelan.html>
- Samson, J. (1977), on *L'isle joyeuse* — as quoted in the file's annotations.

## 🙏 Status / How to contribute

Proof-of-concept, meant to be used and corrected. Contributions and suggestions are welcome: open
an issue, or a pull request against the `.reascale` file.

## License

[MIT](LICENSE) — Copyright (c) 2026 Giorgio Robino.
