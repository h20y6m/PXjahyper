PXjahyper Package
=================

LaTeX: Hyperref support for pLaTeX

This package adjusts the behavior of hyperref on (u)pLaTeX so that authors
can properly create PDF documents that contain document information in
Japanese.

  * Support for PDF strings containing Japanese characters.
  * Support for magnification settings.

### System Requirements

  * TeX format: LaTeX.
  * TeX engine: pTeX, upTeX, pTeX-ng.  
    Some features require the e-TeX extension.
  * DVI-ware: dvipdfmx.
  * Dependent packages:
      - atbegshi
      - hyperref
  * Packages required by some features:
      - japanese-otf
      - etoolbox
      - bxjatoucs

### Installation

  - `*.sty`, `*.def` → $TEXMF/tex/platex/PXjahyper

### License

This package is distributed under the MIT License.


The pxjahyper Package ー main
-----------------------------

Please refer to the manual `pxjahyper.pdf` (in Japanese) for detail.


The pxjahyper-enc Package ー Encoding setting
---------------------------------------------

This is a single-feature package excerpted from the pxjahyper package,
and is provided for internal use from other packages.

It only issues a  "tounicode special” for specifying the encoding of
the PDF strings in the output DVI file.


Revision History
----------------

  * Version 0.6a 〈2020/10/10〉
  * Version 0.6  〈2020/10/05〉
  * Version 0.5b 〈2020/10/04〉
  * Version 0.5a 〈2020/09/27〉
  * Version 0.5  〈2020/06/13〉
  * Version 0.4b 〈2020/04/24〉
  * Version 0.4a 〈2019/11/23〉
  * Version 0.4  〈2019/10/25〉
  * Version 0.3e 〈2019/06/20〉
  * Version 0.3d 〈2018/07/15〉
  * Version 0.3c 〈2018/01/25〉
  * Version 0.3b 〈2018/01/13〉
  * Version 0.3a 〈2017/10/17〉
  * Version 0.3  〈2012/05/28〉
  * Version 0.2  〈2012/05/27〉

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
