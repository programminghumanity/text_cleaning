# List of text cleaning scripts



[TOC]

## Basic cleaning steps

Modules that contain a set of functions and that can be imported and used in Python.



### clean-text

* **Description**: Data on the Web and elsewhere is often dirty. Clean your text with `clean-text` to create normalized text representations. 
* **Type**: Python module

* **Link**: https://github.com/jfilter/clean-text
* **License**: Apache
* **Languages supported**: English and German
* **Functionalities**:
  * Fix unicode errors ()
  * Translate to closest ASCII representation
  * Lowercase text
  * Strip line breaks
  * Replace URLs with a special token
  * Replace email addresses with a special token
  * Replace phone numbers with a special token
  * Replace numbers with a special token
  * Replace digits with a special token
  * Replace currency symbols with a special token
  * Remove punctuation



### textcleaner

* **Description**: Text-Cleaner is a utility library for text-data pre-processing. Use it before passing the text data to a model.
* **Type**: Python module

* **Link**: https://github.com/YugantM/textcleaner
* **License**: MIT
* **Languages supported**: English and German
* **Functionalities**:
  * main_cleaner to do all the below in one call ! or
  * remove unnecessary blank lines
  * stip out a perticular character or default one
  * transfer all characters to lowercase if needed
  * remove numbers, symblos and stop-words from the whole text
  * tokenize the text-data on one call
  * stemming & lemmatization powered by NLTK



### nltk

* **Description**:  Python modules, data sets, and tutorials supporting research and development in Natural Language Processing.
* **Type**: Python module & data sets

* **Link**: https://github.com/nltk/nltk
* **License**: Apache
* **Languages supported**: RSLPStemmer (Portuguese), ISRIStemmer (Arabic), and SnowballStemmer (Danish, Dutch, English, Finnish, French, German, Hungarian, Italian, Norwegian, Portuguese, Romanian, Russian, Spanish, Swedish
* **Functionalities**:
  * split text into sentences 
  * split text into words
  * stop words filtering
  * access to corpora
  * stemming and lemmatization
  * POS tagging
  * normalization


### spacy

* **Description**: spaCy is a library for advanced Natural Language Processing in Python and Cython. (Useful for production level code)
* **Type**: Python module

* **Link**: https://github.com/explosion/spaCy
* **License**: Apache
* **Languages supported**: 50+ languages
* **Functionalities**:
  Text cleaning -
  * Non-destructive tokenization
  * Named entity recognition
  Analysis - 
  * pretrained statistical models and word vectors
  * Part-of-speech tagging
  * Labelled dependency parsing
  * Syntax-driven sentence segmentation
  * Built in visualizers for syntax and NER
  * Convenient string-to-hash mapping
  * Export to numpy data arrays
  * Efficient binary serialization
  

## Text extractors / parsers

### textract

* **Description**: 
* **Type**:
* **Link**: https://textract.readthedocs.io/en/stable/index.html
* **License**: MIT
* **Functionalities**:
   * .csv via python builtins
   * .doc via antiword
   * .docx via python-docx2txt
   * .eml via python builtins
   * .epub via ebooklib
   * .gif via tesseract-ocr
   * .jpg and .jpeg via tesseract-ocr
   * .json via python builtins
   * .html and .htm via beautifulsoup4
   * .mp3 via sox, SpeechRecognition, and pocketsphinx
   * .msg via msg-extractor
   * .odt via python builtins
   * .ogg via sox, SpeechRecognition, and pocketsphinx
   * .pdf via pdftotext (default) or pdfminer.six
   * .png via tesseract-ocr
   * .pptx via python-pptx
   * .ps via ps2text
   * .rtf via unrtf
   * .tiff and .tif via tesseract-ocr
   * .txt via python builtins
   * .wav via SpeechRecognition and pocketsphinx
   * .xlsx via xlrd
   * .xls via xlrd

### PyPDF2

* **Description**: PyPDF2 is a pure-python PDF library capable of splitting, merging together, cropping, and transforming the pages of PDF files
* **Type**: Python module
* **Link**: https://github.com/mstamy2/PyPDF2
* **License**: BSD License
* **Functionalities**
  * extracting document information (title, author, …)
  * splitting documents page by page
  * merging documents page by page
  * cropping pages
  * merging multiple pages into a single page
  * encrypting and decrypting PDF files



### pdfminer

* **Description**: Tool for extracting information from PDF documents. It focuses on getting and analyzing text data
* **Type**: Python module
* **Link**: https://github.com/pdfminer/pdfminer.six
* **License**
* **Functionalities**:
  * Parse, analyze, and convert PDF documents
  * PDF-1.7 specification support
  * CJK languages and vertical writing scripts support
  * Various font types (Type1, TrueType, Type3, and CID) support
  * Support for extracting images (JPG, JBIG2 and Bitmaps)
  * Support for RC4 and AES encryption
  * Table of contents extraction
  * Tagged contents extraction
  * Automatic layout analysis



### Tika 

* **Description**: Toolkit which detects and extracts metadata and text from over a thousand different file types (such as PPT, XLS, and PDF).
* **Type**: Python port of the [Apache Tika](http://tika.apache.org/) library (requires Java 7+)
* **Link**: https://github.com/chrismattmann/tika-python
* **License**: [Apache License, version 2](http://www.apache.org/licenses/LICENSE-2.0)

* **Functionalities**: 
  * Parse, analyze, and convert PDF documents
  * Specify Output Format To XHTML
  * Unpack interface that handles both metadata and text extraction
  * Detect interface which provides a classification for the provided file
  * Language detection + translation



### PyMuPDF

* **Description**: detects headings from PDfs
* **Type**: Python module
* **Link**: https://towardsdatascience.com/extracting-headers-and-paragraphs-from-pdf-using-pymupdf-676e8421c467
* **License**: GNU GPL V3
* **Functionalities**:
  * decrypt the document
  * access meta information, links and bookmarks
  * render pages in raster formats (PNG and some others), or the vector format SVG
  * search for text
  * extract text and images
  * convert to other formats: PDF, (X)HTML, XML, JSON, text



### Xpdf

* **Description**:  Iincludes a PDF viewer along with a collection of command line tools which perform various functions on PDF files
* **Type**: console line tool
* **Link**: http://www.xpdfreader.com/about.html

* **License** Open source
* **Functionalities**:
  * **xpdf**: PDF viewer ([click for a screenshot](http://www.xpdfreader.com/img/screenshot.png))
  * **pdftotext**: converts PDF to text
  * **pdftops**: converts PDF to PostScript
  * **pdftoppm**: converts PDF pages to netpbm (PPM/PGM/PBM) image files
  * **pdftopng**: converts PDF pages to PNG image files
  * **pdftohtml**: converts PDF to HTML
  * **pdfinfo**: extracts PDF metadata
  * **pdfimages**: extracts raw images from PDF files
  * **pdffonts**: lists fonts used in PDF files
  * **pdfdetach**: extracts attached files from PDF files



### Corpus Crawler

* **Description**: This crawler helps to build corpora from online texts.
* **Type**: command line tool
* **Link**: https://github.com/google/corpuscrawler
* **License**: Apache License Version 2.0 
* **Functionalities**
  * follows links to publicly accessible web pages known to be written in a certain language
  * removes boilerplate and HTML markup
  * writes its output into plaintext files



### BeautifulSoup

* **Description**: library for pulling data out of HTML and XML files
* **Type**: Python module
* **Link**: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
* **License**: MIT
* **Functionalities**
  * gets data out of HTML, XML, and other markup languages
  * pull particular content from a webpage
  * cleans / remove the HTML markup
  * save the information
  * very good intro for social scientists here: https://programminghistorian.org/en/lessons/intro-to-beautiful-soup
  
  
  
### GROBID

* **Description**:  GeneRation Of BIbliographic Data - GROBID is a machine learning library for extracting, parsing and re-structuring raw documents such as PDF into structured XML/TEI encoded documents with a particular focus on technical and scientific publications
* **Type**: API
* **Link**: https://github.com/kermitt2/grobid
* **License**: Apache
* **Functionalities**:
  * Header extraction and parsing from article in PDF format. 
  * References extraction and parsing from articles in PDF format
  * Citation contexts recognition and linking to the full bibliographical references of the article. 
  * Parsing of references in isolation (around 0.89 f-score).
  * Parsing of names (e.g. person title, forenames, middlename, etc.), in particular author names in header, and * author names in references (two distinct models).
  * Parsing of affiliation and address blocks.
  * Parsing of dates, ISO normalized day, month, year.
  * Full text extraction and structuring from PDF articles.
  * Consolidation/resolution of the extracted bibliographical references using the biblio-glutton service or the * * * CrossRef REST API. 
  * Extraction and parsing of patent and non-patent references in patent publications.
  * PDF coordinates for extracted information.



### pattern

* **Description**:  Web mining module for Python, with tools for scraping, natural language processing, machine learning, network analysis and visualization
* **Type**: module
* **Link**: https://github.com/clips/pattern
* **License**: Apache
* **Functionalities**:
  * Data Mining: web services (Google, Twitter, Wikipedia) 
  * Web crawler
  * HTML DOM parser
  * Natural Language Processing: part-of-speech taggers, n-gram search, sentiment analysis, WordNet
  * Machine Learning: vector space model, clustering, classification (KNN, SVM, Perceptron)
  * Network Analysis: graph centrality and visualization.
