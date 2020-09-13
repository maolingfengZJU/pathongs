# FASTA 格式

---

序列的最基本格式，只需要一个`>`符号表示序列开始，后跟序列名称。再换一行内容为DNA或蛋白质序列。

```
>AB000263 | acc=AB000263|descr=Homo sapiens mRNA for prepro cortistatin like peptide, complete cds.| len=368
ACAAGATGCCATTGTCCCCCGGCCTCCTGCTGCTGCTGCTCTCCGGGGCCACGGCCACCGCTGCCCTGCC
CCTGGAGGGTGGCCCCACCGGCCGAGACAGCGAGCATATGCAGGAAGCGGCAGGAATAAGGAAAAGCAGC
CTCCTGACTTTCCTCGCTTGGTGGTTTGAGTGGACCTCCCAGGCCAGTGCCGGGCCCCTCATAGGAGAGG
AAGCTCGGGAGGTGGCCAGGCGGCAGGAAGGCGCACCCCCCCAGCAATCCGCGCGCCGGGACAGAATGCC
CTGCAGGAACTTCTTCTGGAAGACCTTCTCCTCCTGCAAATAAAACCTCACCCATGAATGCTCACGCAAG
TTTAATTACAGACCTGAA
```

一个fasta格式的文件也可以包含多条序列：

```
>seq1
ATCCGGACCGGA
>seq2
CCGGATTGAGGA
>seq3
ACCGGAGATTTG
```

#### Reference

1. http://www.cnblogs.com/ace9/archive/2011/04/29/2032716.html