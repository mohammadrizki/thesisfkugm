# Latex Template for Thesis Writing at FK UGM

## Info
This template is a modification from [LaTeX Template for Thesis Writing at DTETI UGM](https://github.com/canggihpw/thesisdtetiugm). It can be used for bachelor, master, and doctoral thesis at FK UGM, even though for the last one, it still can be considered as a "beta" release. Send me email or create pull-request if you have improvements for this template.

## What's new
[2020-01-28] You can use command **\printendorsementpdf** to include your own pdf file containing the endorsement. Otherwise, use **\printendorsement**

## How-to-use 
Read the detailed information in **thesis_template.tex**.
In case some **sty files** are not available in your TeX installation, just copy the required one from **packages/** directory into the same directory as **thesis_template.tex**. Hopefully this will help beginner users.

## Content:
### Main files
```
|-- thesisfkugm.cls (Class file)
|-- thesis_template.tex (The template file)
```
### Content directory
This directory and the subdirectories are not compulsory. I arranged in such a way to make it easier in writing.
```
|-- contents/
    |-- nomenclature/
    	|-- nomenclature.tex
    |-- statement/
    	|-- statement.tex
    |-- endorsement/
    	|-- endorsement.pdf
    |-- preface/
    	|-- preface.tex
    |-- abstract/
    	|-- abstract.tex
        |-- intisari.tex
    |-- chapter-1/
    	|-- chapter-1.tex
    |-- chapter-2/
    	|-- chapter-2.tex
        |-- sample-fig.png
    |-- chapter-3/
    	|-- chapter-3.tex
    |-- chapter-4/
    	|-- chapter-4.tex
    |-- chapter-5/
    	|-- chapter-5.tex
    |-- appendix/
    	|-- appendix.tex
```
### Additional files
```
|-- packages/ (Additional sty files for helping beginner users)
|-- references.bib (Bibtex file)
```
### Sample directory
Only used for template sample.
```
|-- sample/
    |-- logougm.png
    |-- sample_code.m
    |-- scanned-endorsement.jpg
    |-- scanned-statement.jpg
```

## License
MIT License
