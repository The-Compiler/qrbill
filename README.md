# qrbill – create QR-bills based on the swiss payment standard

Copyright (C) Marei Peischl (peiTeX)  <marei@peitex.de>, 2020–2022

This work is part of a collaborative project of Marei Peischl (peiTeX) and Alex Antener (foobar LLC).

qrbill 2022/07/02 v1.04

***************************************************************************

 This material is subject to the LaTeX Project Public License version 1.3c
 or later. See http://www.latex-project.org/lppl.txt for details.

***************************************************************************

## Provided files

* README.md
* qrbill.dtx
* qrbill.ins
* qrbill-vocab.csv
* qrbill_swiss-cross.pdf

The files
* qrbill.sty
* swiss.qrbill-cfg.tex
* epc.qrbill-cfg.tex
as well as the demo files
* qrbill-standalone-demo.tex
* qrbill-letter-demo.tex
can be created from the qrbill.dtx by processing the qrbill.ins-file.

## Installation Notes

To be able to compile the package, the files
qrbill.sty, swiss.qrbill-cfg.tex, qrbill_swiss-cross.pdf and qrbill-vocab.csv
have to be placed in the $TEXINPUTS path.

To simplify this, you can have a look at the qrbill.tds.zip, which provides an already prestructured variant to be extracted to any tds tree.


## Version History

 * v1.00 (2020-06-28) First official version
 * v1.01 (2020-06-29) Add tds package and the separate option
 * v1.02 (2020-08-25)
   - Fix placement issue with separate option
   - Add sep-iban/sep-reference mechanism
   - Not on version number inconsistency
 * v1.03 (2021-05-10)
   - Update to swiss qrbill payments standard v2.2
   - Add seb-iban and sep-reference to the example files
 * v1.04 (2022/07/02)
   - add basic support for EPC QR codes
   - add date parsing mechanism to preset the dates to values of `\today`