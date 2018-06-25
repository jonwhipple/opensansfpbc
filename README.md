# Open Sans – First Peoples of British Columbia
This is an Open Sans variant to add coverage for all the orthographies of the languages of the First Peoples of British Columbia.

## Goals

The primary goal of this project is to expand the language coverage of Open Sans to support the orthographies of all the languages of all the First Peoples of British Columbia. Bitish Columbia is home to 60% of First Nations languages in Canada with 34 unique languages ( [Report on the Status of B.C. First Nations Languages 2014, Second Edition, Fact Sheet](http://www.fpcc.ca/files/PDF/Language/2014_Language_Report_Fact_Sheet.pdf) – PDF ).

The secondary, but no less important goal, is to complete and test the expanded fonts and submit to Google Fonts for reintegration into Open Sans.

## Language Coverage

At time of this writing (2018-06-23), the fonts provide _qualified coverage_ for **Hul’q’umi’num’ / Halq'eméylem / hən̓q̓əmin̓əm**, as well as **International Phonetic Alphabet**, in addition to the coverage of normally provided by Open Sans.

Qualified coverage means that some weights are complete and others are not yet, but have sufficient coverage for use in https://www.vpl.ca

The following weights are incomplete:
- Regular
- Italic
- Semibold
- Semibold-Italic
- ExtraBold
- ExtraBold-Italic

## Directory Structure

`dist` contains compressed (`.zip`) archives of compiled binaries in 5 flavours:
- Embedded OpenType (`.eot`)
- OpenType Font (`.otf`)
- TrueType Font (`.ttf`)
- Web Open Font Format File (`.woff`)
- Web Open Font Format 2.0 File (`.woff2`)

`documentation` contains the design brief as well as other notes and files.

`fonts` contains compiled binary font files as a reference (see [Google Fonts Quick Start](https://github.com/googlefonts/gf-docs/blob/master/QuickStartGlyphs.md) )

`sources` contains source `.glyphs` files
