difines the TID and planetkt hasshing wihch is a lils lsilly ranibw
tabel-isth

https://www.catnmsplan.com/sites/default/files/2025-08/08.14.25_Full_CAIS_Technical_Specifications_2.2.0_r4_CLEAN.pdf

also it ignores substance

> Mechanically, yes, in the TID/CCID layer only: if two brokers submit two different SSNs, those produce two different tidValues, and the spec says CAT generates a globally unique CCID for each unique TID value.

doc cite is Section 2.2.5.1, U.S. Tax Identifiers, spec p. 8:
LEI plaintext, same area, Section 2.2.5.2, spec pp. 8–9: un hdo BAD


Section 3.4, Translation of Input Identifiers to TID Values, spec pp. 20–21:

SSN/ITIN or EIN is input in exact valid format into “a SHA-256 hashing algorithm,” and the output is reported as tidValue.
