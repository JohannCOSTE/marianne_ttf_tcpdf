# marianne_ttf_tcpdf
Here are ttf and tcpdf font files of official French government font « Marianne ». 
I share this work because I spend a lots of time with online converters from otf to tff with this font and each time the resulting tff files was messing my generated pdf.

## How I proceed
### Create the ttf font
I only way I found in order to fix my problem described above is to download [FontForge](https://fontforge.org/en-US/), create a new font, a copy only the glyphes I need from the otf file opened also in another windows of FontForge.
Then a simply done a "Generate font" to ttf format.

### Add it to tcpdf
There are several tutorials to do so like [this one](https://queirozf.com/entries/adding-a-custom-font-to-tcpdf#new-way). But you can also put the files in the directory `tcpdf of this repository to the directory `fonts` of tcpdf.

### Use them
To use them you just have to set the right `font-family`:
* For Marianne-Bold : `font-family: 'marianneb'`
* For Marianne-Light : `font-family: 'mariannelight'`
* For Marianne-Regular : `font-family: 'marianne'`
* For Marianne-RegularItalic : `font-family: 'mariannei'`

## Disclaimer
All the set of Marianne font is copyrighted to the *French government information service*. To have more information about this font, consult [this website](https://api.media.atlassian.com/file/51f8cb41-c881-43f2-a9c6-4f74e1d9b4de/binary?client=ea1921d4-b72c-44f1-a160-93a12d658189&collection=contentId-223019527&dl=true&max-age=2592000&token=eyJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJlYTE5MjFkNC1iNzJjLTQ0ZjEtYTE2MC05M2ExMmQ2NTgxODkiLCJhY2Nlc3MiOnsidXJuOmZpbGVzdG9yZTpjb2xsZWN0aW9uOmNvbnRlbnRJZC0yMjMwMTk1MjciOlsicmVhZCJdfSwiZXhwIjoxNjM4Njk3NjM5LCJuYmYiOjE2Mzg2OTQ2OTl9.bYAV7DcG9LjV2XO6-ivg0yOPvufPs7wRvGp9U_M47jw). You can download the originals' font files [here](https://api.media.atlassian.com/file/51f8cb41-c881-43f2-a9c6-4f74e1d9b4de/binary?client=ea1921d4-b72c-44f1-a160-93a12d658189&collection=contentId-223019527&dl=true&max-age=2592000&token=eyJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJlYTE5MjFkNC1iNzJjLTQ0ZjEtYTE2MC05M2ExMmQ2NTgxODkiLCJhY2Nlc3MiOnsidXJuOmZpbGVzdG9yZTpjb2xsZWN0aW9uOmNvbnRlbnRJZC0yMjMwMTk1MjciOlsicmVhZCJdfSwiZXhwIjoxNjM4Njk3NjM5LCJuYmYiOjE2Mzg2OTQ2OTl9.bYAV7DcG9LjV2XO6-ivg0yOPvufPs7wRvGp9U_M47jw).

## Sources
- FontForge : https://fontforge.org/en-US/
- Custom TCPDF font : https://queirozf.com/entries/adding-a-custom-font-to-tcpdf#new-way
- Wikipedia about Marianne font : https://fr.wikipedia.org/wiki/Marianne_(police_d%27%C3%A9criture)
- French government page about Marianne font : https://www.gouvernement.fr/charte/charte-graphique-les-fondamentaux/la-typographie
- Official Design system page (dev oriented) of Marianne font : https://gouvfr.atlassian.net/wiki/spaces/DB/pages/223019527/Typographie+-+Typography