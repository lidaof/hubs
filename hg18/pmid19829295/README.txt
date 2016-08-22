Each files contain basecall information at all C reference positions on a
chromosome in the hg18 reference sequence for the shotgun bisulfite sequencing
of H1 embryonic stem cells as described in the following publication:

Ryan Lister, Mattia Pelizzola, Robert H. Dowen, R. David Hawkins, Gary Hon,
Julian Tonti-Filippini, Joseph R. Nery, Leonard Lee, Zhen Ye, Que-Minh Ngo,
Leed Edsall, Jessica Antosiewicz-Bourget, Ron Stewart, Victor Ruotti,
A. Harvey Millar, James A. Thomson, Bing Ren & Joseph R. Ecker
Human DNA methylomes at base resolution show widespread epigenomic
differences.
Nature Vol 462, 19 November 2009/doi:10.1038/nature08514

Example data:
12      16523   +       CG      7       4       11
12      16524   -       CG      6       2       8
12      16531   -       CHH     0       8       8
12      16536   -       CHH     0       9       9

Column 1: chromosome/assembly
Column 2: reference coordinate (0-based system)
Column 3: strand the cytosine is located on
Column 4: context of the cytosine (CG, CHG, CHH, where H = A, C, or T)
Column 5: number of cytosines sequenced in all reads covering this position
Column 6: number of thymines sequenced in all reads covering this position
Column 7: number of reads covering this position

For any queries please contact Ryan Lister (lister@salk.edu).
