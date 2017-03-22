# Genome Assembly Gaps
Ronica K  



#Mouse Genome Assemblies

downloaded from UCSC



##GRCm38/mm10 (Dec. 2011)

```
## GRanges object with 574 ranges and 3 metadata columns:
##         seqnames               ranges strand |   status       type
##            <Rle>            <IRanges>  <Rle> | <factor>   <factor>
##     [1]     chr1 [       1,   100001]      * |        N   telomere
##     [2]     chr1 [  100001,   110001]      * |        N  short_arm
##     [3]     chr1 [  110001,  3000001]      * |        N centromere
##     [4]     chr1 [ 3002130,  3003119]      * |        N      other
##     [5]     chr1 [22424868, 22424968]      * |        N      other
##     ...      ...                  ...    ... .      ...        ...
##   [570]     chrY [66452982, 66502982]      * |        N      other
##   [571]     chrY [69457735, 69538735]      * |        N     contig
##   [572]     chrY [87340086, 87370086]      * |        N     contig
##   [573]     chrY [90844699, 91644699]      * |        N     contig
##   [574]     chrY [91644699, 91744699]      * |        N   telomere
##           bridge
##         <factor>
##     [1]       no
##     [2]       no
##     [3]       no
##     [4]      yes
##     [5]      yes
##     ...      ...
##   [570]      yes
##   [571]       no
##   [572]       no
##   [573]       no
##   [574]       no
##   -------
##   seqinfo: 21 sequences from mm10 genome; no seqlengths
```

###Gap Types

__clone__ - gaps between clones

__contig__ - gaps between map contigs, various sizes

__telomere__ - 42 gaps for telomeres (100,000 Ns)

__centromere__ - 20 gaps for centromeres (size: 2,890,000 Ns)

__short_arm__ - 21 gaps for the short arm (10,000 Ns) at base positions 100,001-110,000 of each chromosome

__other__ - sequence of Ns in the assembly that were not marked as gaps in the AGP assembly definition file, various sizes

__fragment__ - a single gap of 31 bases in chrX_GL456233_random



```
## 
## centromere      clone     contig   fragment      other  short_arm 
##         20          4        104          0        383         21 
##   telomere 
##         42
```


##NCBI37/mm9 (July 2007)

```
## GRanges object with 562 ranges and 3 metadata columns:
##         seqnames                 ranges strand |   status       type
##            <Rle>              <IRanges>  <Rle> | <factor>   <factor>
##     [1]     chr1   [       1,  3000001]      * |        N centromere
##     [2]     chr1   [22414949, 22415049]      * |        N   fragment
##     [3]     chr1   [22423350, 22473350]      * |        N     contig
##     [4]     chr1   [24686639, 24736639]      * |        N   fragment
##     [5]     chr1   [75102131, 75118131]      * |        N     contig
##     ...      ...                    ...    ... .      ...        ...
##   [558]     chrX [166527507, 166577507]      * |        N     contig
##   [559]     chrY [  2195327,   2345327]      * |        N     contig
##   [560]     chrY [  2797388,   2847388]      * |        N   fragment
##   [561]     chrY [  2902556,   5902556]      * |        N centromere
##   [562]     chrY [  5902556,  15902556]      * |        N     contig
##           bridge
##         <factor>
##     [1]       no
##     [2]      yes
##     [3]       no
##     [4]       no
##     [5]       no
##     ...      ...
##   [558]       no
##   [559]       no
##   [560]       no
##   [561]       no
##   [562]       no
##   -------
##   seqinfo: 21 sequences from mm9 genome; no seqlengths
```

###Gap Types

__fragment__ - gaps between the contigs of a draft clone

__contig__ - gaps between map contigs

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies)


```
## 
## centromere     contig   fragment 
##         21        105        436
```


##NCBI36/mm8 (Feb. 2006)

```
## GRanges object with 1343 ranges and 3 metadata columns:
##          seqnames               ranges strand |   status       type
##             <Rle>            <IRanges>  <Rle> | <factor>   <factor>
##      [1]     chr1 [       1,  3000001]      * |        N centromere
##      [2]     chr1 [22410019, 22410119]      * |        N   fragment
##      [3]     chr1 [22418420, 22420786]      * |        N     contig
##      [4]     chr1 [24670818, 24670918]      * |        N   fragment
##      [5]     chr1 [74988764, 75004764]      * |        N     contig
##      ...      ...                  ...    ... .      ...        ...
##   [1339]     chrY  [1059317,  1109317]      * |        N   fragment
##   [1340]     chrY  [2224287,  2424287]      * |        N   fragment
##   [1341]     chrY  [2729405,  3029405]      * |        N     contig
##   [1342]     chrY  [3029405,  6029405]      * |        N centromere
##   [1343]     chrY  [6029405, 16029405]      * |        N     contig
##            bridge
##          <factor>
##      [1]       no
##      [2]      yes
##      [3]       no
##      [4]      yes
##      [5]       no
##      ...      ...
##   [1339]       no
##   [1340]       no
##   [1341]       no
##   [1342]       no
##   [1343]       no
##   -------
##   seqinfo: 21 sequences from mm8 genome; no seqlengths
```

###Gap Types

__fragment__ - gaps between the contigs of a draft clone

__contig__ - gaps between map contigs

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies)



```
## 
## centromere     contig   fragment 
##         21        104       1218
```


##NCBI35/mm7 (Aug. 2005)

```
## GRanges object with 21266 ranges and 3 metadata columns:
##           seqnames              ranges strand |   status       type
##              <Rle>           <IRanges>  <Rle> | <factor>   <factor>
##       [1]     chr1  [      1, 3000001]      * |        N      clone
##       [2]     chr1  [3276495, 3276595]      * |        N   fragment
##       [3]     chr1  [3284014, 3284372]      * |        N   fragment
##       [4]     chr1  [3287469, 3287569]      * |        N   fragment
##       [5]     chr1  [3295419, 3295519]      * |        N   fragment
##       ...      ...                 ...    ... .      ...        ...
##   [21262]     chrY [1560808,  1610808]      * |        N      clone
##   [21263]     chrY [2024648,  2074648]      * |        N      clone
##   [21264]     chrY [2223454,  2523454]      * |        N     contig
##   [21265]     chrY [2523454,  5523454]      * |        N centromere
##   [21266]     chrY [5523454, 15523454]      * |        N     contig
##             bridge
##           <factor>
##       [1]       no
##       [2]      yes
##       [3]      yes
##       [4]      yes
##       [5]      yes
##       ...      ...
##   [21262]      yes
##   [21263]      yes
##   [21264]       no
##   [21265]       no
##   [21266]       no
##   -------
##   seqinfo: 21 sequences from mm7 genome; no seqlengths
```

###Gap Types

__fragment__ - gaps between the contigs of a draft clone

__clone__ - gaps between clones in the same map contig

__contig__ - gaps between map contigs

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies)



```
## 
## centromere      clone     contig   fragment 
##          1        240         45      20980
```

##Gaps on Chromosome Y

__mm10__


```
## GRanges object with 32 ranges and 3 metadata columns:
##        seqnames               ranges strand |   status      type   bridge
##           <Rle>            <IRanges>  <Rle> | <factor>  <factor> <factor>
##    [1]     chrY   [      1,  100001]      * |        N  telomere       no
##    [2]     chrY   [ 100001,  110001]      * |        N short_arm       no
##    [3]     chrY   [ 363558,  663558]      * |        N    contig       no
##    [4]     chrY   [2939417, 3289417]      * |        N    contig       no
##    [5]     chrY   [3429742, 3729742]      * |        N     other      yes
##    ...      ...                  ...    ... .      ...       ...      ...
##   [28]     chrY [66452982, 66502982]      * |        N     other      yes
##   [29]     chrY [69457735, 69538735]      * |        N    contig       no
##   [30]     chrY [87340086, 87370086]      * |        N    contig       no
##   [31]     chrY [90844699, 91644699]      * |        N    contig       no
##   [32]     chrY [91644699, 91744699]      * |        N  telomere       no
##   -------
##   seqinfo: 21 sequences from mm10 genome; no seqlengths
```

__mm9__


```
## GRanges object with 4 ranges and 3 metadata columns:
##       seqnames              ranges strand |   status       type   bridge
##          <Rle>           <IRanges>  <Rle> | <factor>   <factor> <factor>
##   [1]     chrY [2195327,  2345327]      * |        N     contig       no
##   [2]     chrY [2797388,  2847388]      * |        N   fragment       no
##   [3]     chrY [2902556,  5902556]      * |        N centromere       no
##   [4]     chrY [5902556, 15902556]      * |        N     contig       no
##   -------
##   seqinfo: 21 sequences from mm9 genome; no seqlengths
```

__mm8__


```
## GRanges object with 5 ranges and 3 metadata columns:
##       seqnames              ranges strand |   status       type   bridge
##          <Rle>           <IRanges>  <Rle> | <factor>   <factor> <factor>
##   [1]     chrY [1059317,  1109317]      * |        N   fragment       no
##   [2]     chrY [2224287,  2424287]      * |        N   fragment       no
##   [3]     chrY [2729405,  3029405]      * |        N     contig       no
##   [4]     chrY [3029405,  6029405]      * |        N centromere       no
##   [5]     chrY [6029405, 16029405]      * |        N     contig       no
##   -------
##   seqinfo: 21 sequences from mm8 genome; no seqlengths
```

__mm7__


```
## GRanges object with 8 ranges and 3 metadata columns:
##       seqnames              ranges strand |   status       type   bridge
##          <Rle>           <IRanges>  <Rle> | <factor>   <factor> <factor>
##   [1]     chrY [ 723166,   723266]      * |        N   fragment      yes
##   [2]     chrY [ 742552,   742652]      * |        N   fragment      yes
##   [3]     chrY [1060078,  1260078]      * |        N      clone      yes
##   [4]     chrY [1560808,  1610808]      * |        N      clone      yes
##   [5]     chrY [2024648,  2074648]      * |        N      clone      yes
##   [6]     chrY [2223454,  2523454]      * |        N     contig       no
##   [7]     chrY [2523454,  5523454]      * |        N centromere       no
##   [8]     chrY [5523454, 15523454]      * |        N     contig       no
##   -------
##   seqinfo: 21 sequences from mm7 genome; no seqlengths
```
