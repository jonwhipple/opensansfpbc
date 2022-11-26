# Open Sans – IPA
This is an Open Sans variant to add coverage for all the orthographies of the languages of the First Peoples of British Columbia.

## Goals

# Open Sans – First Peoples of British Columbia
This is an Open Sans variant to add coverage for all the orthographies of the languages of the First Peoples of British Columbia.

British Columbia is unique within Canada when it comes to Indigenous language diversity. In the context of Canada, B.C.’s languages make up more than 50% of the approximately 61 languages indigenous to this country.
• There are 34 First Nations languages within 7 distinct unrelated language families.
• There are 3 languages once spoken that are now sleeping.
• Languages Indigenous to other parts of Canada are now spoken in B.C. because of migration.
( [Report on the Status of B.C. First Nations Languages 2014, Second Edition, Fact Sheet] (https://fpcc.ca/wp-content/uploads/2020/05/FPCC-Fact-Sheet-Language-Report-2018.pdf) – PDF ).

## Goals

The primary goal of this project is to continue support for Vancouver Public Library's use of Open Sans on https//:www.vpl.ca. As First Nations refine how they express their language in written form, changes are necessary. Additionally, VPL has begun to use weights of this type family that were not originally required.

This means that some weights do not have required glyphs. This branch of the project will add those required glyphs in the required weights as needed or as can be undertaken.              

The secondary, but no less important goal, is to complete and test the expanded fonts and submit to Google Fonts for reintegration into Open Sans.

## Language Coverage

At time of this writing (2022-11-26), the fonts provide _qualified coverage_ for **Hul’q’umi’num’ / Halq'eméylem / hən̓q̓əmin̓əm**, as well as **International Phonetic Alphabet**, in addition to the coverage of normally provided by Open Sans.

_Qualified coverage_ means that some weights are complete and others are not yet, but have sufficient coverage for use in https://www.vpl.ca

The following weights provide coverage for **Hul’q’umi’num’ / Halq'eméylem / hən̓q̓əmin̓əm**:
- Light
- LightItalic
- Bold
- BoldItalic

The following weights provide only partial coverage for **Hul’q’umi’num’ / Halq'eméylem / hən̓q̓əmin̓əm**:
- Regular
- Italic
- Semibold
- Semibold-Italic
- ExtraBold
- ExtraBold-Italic

## Directory Structure

`dist` contains compressed (`.zip`) archives of compiled binaries in 4 flavours:
- OpenType Font (`.otf`)
- TrueType Font (`.ttf`)
- Web Open Font Format File (`.woff`)
- Web Open Font Format 2.0 File (`.woff2`)

`documentation` contains the design brief as well as other notes and files.

`fonts` contains compiled binary font files as a reference (see [Google Fonts Quick Start](https://github.com/googlefonts/gf-docs/blob/master/QuickStartGlyphs.md) ).

`sources` contains source `.glyphs` files.