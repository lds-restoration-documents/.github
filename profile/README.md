# Latter-day Saint Restoration Documents

Latter-day Saint Restoration Documents is an effort to use AI tools, and tools built by AI, to transcribe the content of digital photographs of original texts from the history of The Church of Jesus Christ of Latter-day Saints into [Markdown](#what-is-markdown) and Plain Text files. 

![Image Showing a page from the 1830 edition of The Book of Mormon, with Markdown and Plain Text transcriptions](https://github.com/lds-restoration-documents/.github/blob/main/profile/1830-Book-of-Mormon-page-transcription.png)

[Markdown](#what-is-markdown) files can be easily converted into other formats like HTML, PDF, Word, EPUB, Images or JSON. 

AI is also especially good at reading and analyzing [Markdown](#what-is-markdown) files. So transcribing these documents into [Markdown](#what-is-markdown) makes them readily available for use by AI. 

The plain text files are readable by any system and are useful for importing into databases or analyzing with other tools that just need the text without any formatting.

[Currently available transcriptions](#currently-available-texts) include early editions of _The Book of Mormon_, the 1833 _Book of Commandments_, and the 1828 _Phinney Cooperstown Bible_. Additional texts will be added over time. 

For AI, the project has used _Claude Code_ by Anthropic, with the _Sonnet 5.5_ Model, configured with _Medium_ effort.

## AI Transcription

Each page of the original text is transcribed using Artificial Intelligence by analyzing the images of each page, and using programming languages and image manipulation tools to zoom in and out to examine words, letters, and punctuation. The AI generates a separate [Markdown](#what-is-markdown) file for each page, with comments identifying features of the page, as well as uncertain words or punctuation. The AI compares its results to OCR extractions of the same text. The AI then runs an agent to blindly proofread each markdown file and compare it to the original image, identifying discrepancies and ambiguities. All of the generated Python tools are included in each text's git repository, as well as all of the AI documentation.

## Files

Once the [Markdown](#what-is-markdown) files for each page have been created, the AI uses code to generate the following output:
* The whole text in a single [Markdown](#what-is-markdown) file
* The whole text in a single plain text file
* A plain text file containing just the core text, excluding frontmatter &c. (called the "sparse" text) 
* A [Markdown](#what-is-markdown) file cataloging printer's typos and errors that can be identified by AI

## Currently Available Texts

* [1830 Edition of The Book of Mormon](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon/blob/main/book-of-mormon-1830-pages)
  * [book-of-mormon-1830.md](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon/blob/main/book-of-mormon-1830.md)
  * [book-of-mormon-1830.txt](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon/blob/main/book-of-mormon-1830.txt)
  * [book-of-mormon-1830-sparse.txt](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon/blob/main/book-of-mormon-1830-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1830-grandin-palmyra-book-of-mormon/blob/main/printer-typos.md)
    
* [1837 Edition of The Book of Mormon](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon/blob/main/book-of-mormon-1837-pages)
  * [book-of-mormon-1837.md](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon/blob/main/book-of-mormon-1837.md)
  * [book-of-mormon-1837.txt](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon/blob/main/book-of-mormon-1837.txt)
  * [book-of-mormon-1837-sparse.txt](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon/blob/main/book-of-mormon-1837-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1837-pratt-goodson-kirtland-book-of-mormon/blob/main/printer-typos.md)

* [1840 Edition of The Book of Mormon](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon/blob/main/book-of-mormon-1840-pages)
  * [book-of-mormon-1840.md](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon/blob/main/book-of-mormon-1840.md)
  * [book-of-mormon-1840.txt](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon/blob/main/book-of-mormon-1840.txt)
  * [book-of-mormon-1840-sparse.txt](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon/blob/main/book-of-mormon-1840-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1840-robinson-smith-nauvoo-book-of-mormon/blob/main/printer-typos.md)

* [1841 Edition of The Book of Mormon](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon/blob/main/book-of-mormon-1841-pages)
  * [book-of-mormon-1841.md](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon/blob/main/book-of-mormon-1841.md)
  * [book-of-mormon-1841.txt](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon/blob/main/book-of-mormon-1841.txt)
  * [book-of-mormon-1841-sparse.txt](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon/blob/main/book-of-mormon-1841-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1841-young-kimball-pratt-liverpool-book-of-mormon/blob/main/printer-typos.md)

* [1852 Edition of The Book of Mormon](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron/tree/main/book-of-mormon-1852-pages)
  * [book-of-mormon-1852.md](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron/blob/main/book-of-mormon-1852.md)
  * [book-of-mormon-1852.txt](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron/blob/main/book-of-mormon-1852.txt)
  * [book-of-mormon-1852-sparse.txt](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron/blob/main/book-of-mormon-1852-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1852-richards-liverpool-book-of-momron/blob/main/printer-typos.md)

* [1833 Book of Commandments](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments/blob/main/book-of-commandments-1833-pages)
  * [book-of-commandments-1833.md](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments/blob/main/book-of-commandments-1833.md)
  * [book-of-commandments-1833.txt](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments/blob/main/book-of-commandments-1833.txt)
  * [book-of-commandments-1833-sparse.txt](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments/blob/main/book-of-commandments-1833-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1833-phelps-zion-book-of-commandments/blob/main/printer-typos.md)

* [1828 Phinney Cooperstown Bible](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible)
  * [Transcribed Pages](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible/blob/main/phinney-bible-pages)
  * [phinney-bible.md](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible/blob/main/phinney-bible.md)
  * [phinney-bible.txt](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible/blob/main/phinney-bible.txt)
  * [phinney-bible-sparse.txt](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible/blob/main/phinney-bible-sparse.txt)
  * [printer-typos.md](https://github.com/lds-restoration-documents/1828-phinney-cooperstown-bible/blob/main/printer-typos.md)

## What is Markdown?

Markdown is a simple way of writing formatted text using plain characters, such as `#` for headings and `*asterisks*` for *italics*. A Markdown file is still readable as ordinary text, and can also be displayed with formatting. 

* Learn more at [markdown.org](https://markdown.org/).
* Tools for displaying, editing, or converting Markdown files: [https://markdown.org/tools/](https://markdown.org/tools/)

## Disclaimer
This is an individual personal project and is not officially affiliated with [The Church of Jesus Christ of Latter-day Saints](https://www.churchofjesuschrist.org/).
