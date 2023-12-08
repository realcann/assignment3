Question 2: Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene 
by using the string concatenation operator, on the standard output! Note: Feel free to create a 
fictional gene sequence by randomly filling in the gene components by the characters 
corresponding to individual nucleotide bases.

** Answer **

...
promoter ="TAATATAGATAGAACA"
5_UTR ="ACGTAGTAGTAGTCAGT"
start_codon ="ACGTCGAGTCG"      
exon1 ="TGCAGTGAGCGAGT"
intron ="ATGCGGTGCGATGC"
exon2 ="CGTATGAGCGTAGATC"
stop_codon ="GTCGAGCGAGGTTGAAGCGT"  
3_UTR ="GACTGAGTCATGTGACGT"
fav_gene = promoter + 5_UTR +start_codon + exon1 + intron + exon2 + stop_codon +3_UTR
print("my favourite gene sequence is as follows:")
print(fav_gene)
...