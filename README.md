# New Heterodox Mono

A Didone-esque Monospaced Typeface based on Alexey Kryukov's Old Standard TT.

Some years ago I made an adaption of the beautiful open-source font _Old Standard TT_ into a monospaced font
for my own use. I have been using this a lot as my programming font but I had never made it public.
Despite the typeface still has some room for improvement, I decided perhaps I should upload it in case someone
finds this useful or wants to help developing it, as there are almost no free alternatives of this kind of
monospace fonts out there.

I felt that it is very much non-"standard" in the computer science/programming community
to use this kind of typeface in programming, so I named it "New Heterodox" as opposed to
"Old Standard". (Occasionally you may see Century School Book Mono in textbooks but it is definitely not
popular) Ironically, "Old Standard" was named as opposed to "Obyknovennaya Novaya" ("New Standard"), and now in
the age of computers, the old-time new standard has become a new heterodoxy, as in many other things in
design.


# Design Notes

Over the years I have grown increasingly tired of looking at the mainstream sans-serif "programming fonts" all days.
Underlying many of them seems to be a shared vision that only "readability", or in other words, utility, matters;
while aesthetics, elegance and feeling are somewhat a by-product, some sort of an opinion that needs to be justified
_through_ some "objective" reasoning around readability, in which history and tradition have no roles to play. But this
vision is rather awkward in itself: if we go back a hundred years and ask a French whether they find Didot difficult
to read, they may tell you that it is totally readable, as historically it was not uncommon to set newspapers in high-contrast
typefaces like the Didot, while nowadays most people would probably say that Dejavu Mono is more readable for coding. Once
we expand our time horizon a little, it is immediately obvious that much, but of course, not all, reasonings around
readability nowadays are, rather than some objectively derived right-thing-to-be, nothing more than traditions and customs:
one which has been passed down from the days when the resolution of computer screens was too low to accurately display the
serifs.

As a result of this vision, most popular sans-serif programming fonts look minimalistic, or dull, depending on how you
look at it. Serifs are not mission-critical, let's remove them. Creativity and irregularity is discouraged by
default unless there are some arguments for its utility.

But if utility were the only thing that matters, why don't we write programs in a monospaced version of Comic Sans? A
quick Google will show you that Comic Sans is very legible at small size. It feels wrong, of course, because the _feeling_ of a
piece of art work matters. Serifed types are attractive for programming because they evoke a feeling of thoughtfulness.

But how readable is this font? I am comfortable programming with it everyday but perhaps the right person to answer this
question is you, rather than me.


# Some details

The design of the letterforms has been modified from Old Standard to adapt to monospace -- especially,
the proportion of the letters, in this typeface, significantly deviates from Old Standard to adapt to
the monospaced typesetting environment. This, of course, changes the texture and rhythm of the entire
typeface, but my goal is, instead, to find a new proportion that works for monospace rather than to
keep the slim-looking modern serif tradition; as it is pretty much impossible to maintain the same rhythm
in a monospaced type as in a proportional type.

For the letterform, some glyphs such as 'f', 'r', 'j' etc. look quite unorthodoxical with respect to the historical
norm. This is perhaps not driven by necessity, but, rather, by taste. I don't like Century Schoolbook Mono's
approach, which prioritises keeping more 'agreeable' letterforms over making the amount of whitespace between
letters more uniform. So for some glyphs I have got a little creative, liberally deviating from the tradition while
still taken care to retain the metalish feeling. Also the contrast has been slightly adjusted compared to Old
Standard in order to improve readability in small size.

The typeface, at the current stage, is pretty usable for the purpose of scientific/system programming or
typesetting articles, especially if you only need Western European glyphs. For web programming - perhaps you will find
some less frequently used signs missing, such as the Japanese yen, or the footnote dagger sign.

Further improvement may be to add more glyphs/language support. Greeks would be my priority if I had time because
science is what I use this typeface for. Of course, any contribution is welcome.

# Linux Font Rendering

Finally, if you find the font appearing "glitchy" in some Linux editors (such as emacs) then you probably have
a mis-configured font rendering engine. My personal experience is that Qt is more likely to have out-of-box
good font rendering.


# Screenshots

![Screenshot 1](https://github.com/hckiang/font-new-heterodox-mono/blob/fc9901a91e239494f11406eb86a96e8f8c4bda3b/screenshot01.png)
![Screenshot 2](https://github.com/hckiang/font-new-heterodox-mono/blob/fc9901a91e239494f11406eb86a96e8f8c4bda3b/screenshot02.png)
