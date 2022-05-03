# PhD Thesis (Univ. Grenoble Alpes)

This project contains the `TeX` sources of my doctoral dissertation on the work I've done between 2018 and 2022 in the TIMA laboratory, at Univ. Grenoble Alpes.

It is based on a previous template from [asherikov](https://github.com/asherikov/phd-thesis), adapted to my own needs, with small updates on the front page to cope with the new UGA visual identity and french legislation.

## Useful `TeX` commands and project features

Some useful packages - but also custom macros - are integrated in the `TeX` template:

* the `todo` package can be used to mark tasks to do - you can use custom defined type of tasks! - and summarize them in a list at the beginning of the draft document
* a custom `glossary` package is provided. It is quite basic, but works well

Moreover, the provided Makefile provides some interesting features, which are explained in it:

* spell checking
* sub range extracting, including the individual extraction of each chapter
* gray sampling (for colorblind friendly documents)
* counting helpers for words and citation numbers

Last but not least, the chapters style (*mainly, the headers*) is custom made - you should change it, as I'm not that confident in my tastes.

## Disclaimers

#### Project support
This project won't be supported much after I'm gone.
It is provided as a basis of work for PhD candidate from UGA, and the different features should be self explanatory for experienced `LaTeX`/`GNU make` users.
However, if you really got some question on how this works, do not hesitate to open an issue, I'll try to answer as soon as possible.

#### PDF generation and layout
This thesis will be uploaded to [the french website for doctoral dissertation](https://theses.fr), however there is no guarantee that the uploaded result will be similar to whatever you compile from source.
More specially, I'm kind of annoyed with unperfect layout, and a lot of manual layout has been done, which might not be cross-platform.
However, it should work good if you don't plan to manual tune the whole layout like I did.


<hr/>

## Contact
© 2022 Bruno FERRES - bruno.ferres%%\[at\]%%grenoble-inp.org
