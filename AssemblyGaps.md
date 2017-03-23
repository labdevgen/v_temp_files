# Genome Assembly Gaps
Ronica K  





# Mouse Genome Assemblies

## GRCm38/mm10 (Dec. 2011)


```
## GRanges object with 686 ranges and 3 metadata columns:
##               seqnames               ranges strand |   status       type
##                  <Rle>            <IRanges>  <Rle> | <factor>   <factor>
##     [1]           chr1 [       1,   100000]      * |        N   telomere
##     [2]           chr1 [  100001,   110000]      * |        N  short_arm
##     [3]           chr1 [  110001,  3000000]      * |        N centromere
##     [4]           chr1 [ 3002130,  3003118]      * |        N      other
##     [5]           chr1 [22424868, 22424967]      * |        N      other
##     ...            ...                  ...    ... .      ...        ...
##   [682] chrUn_GL456393       [53788, 53887]      * |        N      clone
##   [683] chrUn_GL456394       [ 1035,  2612]      * |        N      clone
##   [684] chrUn_GL456394       [20897, 21977]      * |        N      clone
##   [685] chrUn_GL456396       [ 7730,  8220]      * |        N      clone
##   [686] chrUn_GL456396       [11697, 11940]      * |        N      clone
##           bridge
##         <factor>
##     [1]       no
##     [2]       no
##     [3]       no
##     [4]      yes
##     [5]      yes
##     ...      ...
##   [682]      yes
##   [683]      yes
##   [684]      yes
##   [685]      yes
##   [686]      yes
##   -------
##   seqinfo: 44 sequences from mm10 genome
```

### Gap Types

__clone__ - gaps between clones.

__contig__ - gaps between map contigs, various sizes.

__telomere__ - 42 gaps for telomeres (100,000 Ns).

__centromere__ - 20 gaps for centromeres (size: 2,890,000 Ns).

__short_arm__ - 21 gaps for the short arm (10,000 Ns) at base positions 100,001-110,000 of each chromosome.

__other__ - sequence of Ns in the assembly that were not marked as gaps in the AGP assembly definition file, various sizes.

__fragment__ - a single gap of 31 bases in chrX_GL456233_random.



```
## 
## centromere      clone     contig   fragment      other  short_arm 
##         20        114        104          1        384         21 
##   telomere 
##         42
```

## NCBI37/mm9 (July 2007)


```
## GRanges object with 1011 ranges and 3 metadata columns:
##              seqnames               ranges strand |   status       type
##                 <Rle>            <IRanges>  <Rle> | <factor>   <factor>
##      [1]         chr1 [       1,  3000000]      * |        N centromere
##      [2]         chr1 [22414949, 22415048]      * |        N   fragment
##      [3]         chr1 [22423350, 22473349]      * |        N     contig
##      [4]         chr1 [24686639, 24736638]      * |        N   fragment
##      [5]         chr1 [75102131, 75118130]      * |        N     contig
##      ...          ...                  ...    ... .      ...        ...
##   [1007] chrUn_random   [5884087, 5884186]      * |        N   fragment
##   [1008] chrUn_random   [5892169, 5892268]      * |        N   fragment
##   [1009] chrUn_random   [5894720, 5896266]      * |        N   fragment
##   [1010] chrUn_random   [5897640, 5897925]      * |        N   fragment
##   [1011] chrUn_random   [5898884, 5899265]      * |        N   fragment
##            bridge
##          <factor>
##      [1]       no
##      [2]      yes
##      [3]       no
##      [4]       no
##      [5]       no
##      ...      ...
##   [1007]      yes
##   [1008]      yes
##   [1009]      yes
##   [1010]      yes
##   [1011]      yes
##   -------
##   seqinfo: 32 sequences from mm9 genome
```

### Gap Types

__fragment__ - gaps between the contigs of a draft clone.

__contig__ - gaps between map contigs.

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies).


```
## 
## centromere     contig   fragment 
##         21        281        709
```

## NCBI36/mm8 (Feb. 2006)


```
## GRanges object with 1408 ranges and 3 metadata columns:
##              seqnames               ranges strand |   status       type
##                 <Rle>            <IRanges>  <Rle> | <factor>   <factor>
##      [1]         chr1 [       1,  3000000]      * |        N centromere
##      [2]         chr1 [22410019, 22410118]      * |        N   fragment
##      [3]         chr1 [22418420, 22420785]      * |        N     contig
##      [4]         chr1 [24670818, 24670917]      * |        N   fragment
##      [5]         chr1 [74988764, 75004763]      * |        N     contig
##      ...          ...                  ...    ... .      ...        ...
##   [1404] chrUn_random   [1203868, 1253867]      * |        N     contig
##   [1405] chrUn_random   [1272966, 1322965]      * |        N     contig
##   [1406] chrUn_random   [1333015, 1383014]      * |        N     contig
##   [1407] chrUn_random   [1397960, 1447959]      * |        N     contig
##   [1408] chrUn_random   [1450045, 1500044]      * |        N     contig
##            bridge
##          <factor>
##      [1]       no
##      [2]      yes
##      [3]       no
##      [4]      yes
##      [5]       no
##      ...      ...
##   [1404]       no
##   [1405]       no
##   [1406]       no
##   [1407]       no
##   [1408]       no
##   -------
##   seqinfo: 29 sequences from mm8 genome
```

### Gap Types

__fragment__ - gaps between the contigs of a draft clone.

__contig__ - gaps between map contigs.

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies).



```
## 
## centromere     contig   fragment 
##         21        169       1218
```

## NCBI35/mm7 (Aug. 2005)


```
## GRanges object with 26075 ranges and 3 metadata columns:
##               seqnames               ranges strand |   status     type
##                  <Rle>            <IRanges>  <Rle> | <factor> <factor>
##       [1]         chr1   [      1, 3000000]      * |        N    clone
##       [2]         chr1   [3276495, 3276594]      * |        N fragment
##       [3]         chr1   [3284014, 3284371]      * |        N fragment
##       [4]         chr1   [3287469, 3287568]      * |        N fragment
##       [5]         chr1   [3295419, 3295518]      * |        N fragment
##       ...          ...                  ...    ... .      ...      ...
##   [26071] chrUn_random [12765471, 12766470]      * |        N   contig
##   [26072] chrUn_random [12768681, 12769680]      * |        N   contig
##   [26073] chrUn_random [12772252, 12773251]      * |        N   contig
##   [26074] chrUn_random [12774385, 12775384]      * |        N   contig
##   [26075] chrUn_random [12776860, 12777859]      * |        N   contig
##             bridge
##           <factor>
##       [1]       no
##       [2]      yes
##       [3]      yes
##       [4]      yes
##       [5]      yes
##       ...      ...
##   [26071]       no
##   [26072]       no
##   [26073]       no
##   [26074]       no
##   [26075]       no
##   -------
##   seqinfo: 39 sequences from mm7 genome; no seqlengths
```

### Gap Types

__fragment__ - gaps between the contigs of a draft clone.

__clone__ - gaps between clones in the same map contig.

__contig__ - gaps between map contigs.

__centromere__ - gaps from centromeres (3,000,000 Ns) or other large blocks of heterochromatin (size varies).



```
## 
## centromere      clone     contig   fragment 
##          1        240       4854      20980
```


# Chicken Genome Assemblies

## Gallus_gallus-5.0/galGal5 (Dec. 2015)


```
## GRanges object with 1216 ranges and 3 metadata columns:
##          seqnames           ranges strand |   status     type   bridge
##             <Rle>        <IRanges>  <Rle> | <factor> <factor> <factor>
##      [1]     chr1 [  7205,   7304]      * |        U   contig       no
##      [2]     chr1 [ 18686,  18785]      * |        U   contig       no
##      [3]     chr1 [399948, 400047]      * |        U   contig       no
##      [4]     chr1 [437804, 437903]      * |        U   contig       no
##      [5]     chr1 [451315, 451396]      * |        N scaffold      yes
##      ...      ...              ...    ... .      ...      ...      ...
##   [1212] chrLGE64 [114642, 114741]      * |        U   contig       no
##   [1213] chrLGE64 [193129, 193228]      * |        U   contig       no
##   [1214] chrLGE64 [220263, 220362]      * |        U   contig       no
##   [1215] chrLGE64 [428978, 429077]      * |        U   contig       no
##   [1216] chrLGE64 [856252, 856351]      * |        U   contig       no
##   -------
##   seqinfo: 447 sequences from galGal5 genome
```

### Gap Types

__centromere__ - gaps for centromeres are included when they can be reasonably localized (count: 16; all of size 500,000 bases)

__contig__ - gaps between contigs in scaffolds (count: 381; size range: 10 - 50,000 bases)

__scaffold__ - gaps between scaffolds in chromosome assemblies (count: 819; size range: 13 - 156,025 bases)


```
## 
## centromere     contig   scaffold 
##         16        381        819
```

### Known vs Unknown Gap Size


```
## 
##   N   U 
## 859 357
```

## ICGSC Gallus_gallus-4.0/galGal4 (Nov. 2011)


```
## GRanges object with 13898 ranges and 3 metadata columns:
##                           seqnames           ranges strand |   status
##                              <Rle>        <IRanges>  <Rle> | <factor>
##       [1]                     chr1     [1034, 1133]      * |        U
##       [2]                     chr1     [1635, 1734]      * |        U
##       [3]                     chr1     [2505, 2604]      * |        U
##       [4]                     chr1     [3124, 3223]      * |        U
##       [5]                     chr1     [4729, 4828]      * |        U
##       ...                      ...              ...    ... .      ...
##   [13894]                 chrLGE64 [791273, 791372]      * |        U
##   [13895]                 chrLGE64 [792241, 792340]      * |        U
##   [13896] chrLGE64_JH375238_random [  1763,   1862]      * |        U
##   [13897] chrLGE64_JH375239_random [  1769,   1868]      * |        U
##   [13898] chrLGE64_JH375239_random [  4383,   4482]      * |        U
##               type   bridge
##           <factor> <factor>
##       [1]   contig       no
##       [2]   contig       no
##       [3]   contig       no
##       [4]   contig       no
##       [5]   contig       no
##       ...      ...      ...
##   [13894]   contig       no
##   [13895]   contig       no
##   [13896] fragment      yes
##   [13897] fragment      yes
##   [13898] fragment      yes
##   -------
##   seqinfo: 1858 sequences from galGal4 genome; no seqlengths
```

### Gap Types

__fragment__ - gaps between the contigs of a draft clone. 

__contig__ - whole genome sequence contigs.

__other__ - sequences of gaps not marked in the assembly AGP files


```
## 
##   contig fragment    other 
##      915     1948    11035
```

### Known vs Unknown Gap Size


```
## 
##     N     U 
## 12768  1130
```

## WUGSC 2.1/galGal3 (May 2006)


```
## GRanges object with 78478 ranges and 3 metadata columns:
##                seqnames           ranges strand |   status     type
##                   <Rle>        <IRanges>  <Rle> | <factor> <factor>
##       [1]          chr1   [ 5231,  5240]      * |        N fragment
##       [2]          chr1   [ 6541,  6550]      * |        N fragment
##       [3]          chr1   [16469, 16478]      * |        N fragment
##       [4]          chr1   [31259, 31358]      * |        N fragment
##       [5]          chr1   [40054, 40360]      * |        N fragment
##       ...           ...              ...    ... .      ...      ...
##   [78474] chrE64_random [489602, 489765]      * |        N fragment
##   [78475] chrE64_random [507128, 508059]      * |        N fragment
##   [78476] chrE64_random [539187, 540173]      * |        N fragment
##   [78477] chrE64_random [542104, 542113]      * |        N fragment
##   [78478] chrE64_random [554482, 556165]      * |        N fragment
##             bridge
##           <factor>
##       [1]      yes
##       [2]      yes
##       [3]      yes
##       [4]      yes
##       [5]      yes
##       ...      ...
##   [78474]      yes
##   [78475]      yes
##   [78476]      yes
##   [78477]      yes
##   [78478]      yes
##   -------
##   seqinfo: 52 sequences from galGal3 genome
```

### Gap Types

__fragment__ - gaps between the contigs of a draft clone. 

__clone__ - gaps between clones in the same map contig.

Two more types somehow left behind.


```
## 
## centromere      clone     contig   fragment 
##         18        119      17317      61024
```

## WUGSC 1.0/galGal2 (Feb. 2004)


```
## GRanges object with 111817 ranges and 3 metadata columns:
##             seqnames         ranges strand |   status     type   bridge
##                <Rle>      <IRanges>  <Rle> | <factor> <factor> <factor>
##        [1]      chr1 [ 4782,  4963]      * |        N fragment      yes
##        [2]      chr1 [ 6985,  7224]      * |        N fragment      yes
##        [3]      chr1 [ 8579,  9178]      * |        N fragment      yes
##        [4]      chr1 [11437, 11548]      * |        N fragment      yes
##        [5]      chr1 [26706, 26851]      * |        N fragment      yes
##        ...       ...            ...    ... .      ...      ...      ...
##   [111813] chrE50C23 [ 1236,  1543]      * |        N fragment      yes
##   [111814] chrE50C23 [ 3665,  3877]      * |        N fragment      yes
##   [111815] chrE50C23 [ 7215,  7814]      * |        N fragment      yes
##   [111816] chrE50C23 [ 9035, 19034]      * |        N   contig       no
##   [111817] chrE50C23 [19796, 20072]      * |        N fragment      yes
##   -------
##   seqinfo: 51 sequences from galGal2 genome; no seqlengths
```

### Gap Types

__fragment__ - gaps between the Whole Genome Shotgun contigs of a supercontig. (In this context, a contig is a set of overlapping sequence reads. A supercontig is a set of contigs ordered and oriented during the Whole Genome Shotgun process using paired-end reads.) 
These are represented by varying numbers of Ns in the assembly. Fragment gap sizes are usually taken from read pair data.

__clone__ - gaps between supercontigs linked by the fingerprint map. In general, these are represented by 10,000 Ns in the assembly.

__contig__ - gaps between supercontigs not linked by the fingerprint map, but instead by marker data. (In this context, the "Contig" gap type refers to a map contig, not a sequence contig.) In general, these are represented by 10,000 Ns in the assembly for all chromosomes except chrUn (concatenation of unplaced supercontigs), where gaps of 1,000 Ns are used. Gaps of other sizes were used when mRNA or other data suggested possible but not confirmed links between supercontigs.

__centromere__ - gaps for centromeres were included when they could be reasonably localized. These are represented by 1,500,000 Ns in the assembly for the macrochromosomes 1-10 and Z, and by 500,000 Ns for all others (microchromosomes)



```
## 
## centromere      clone     contig   fragment 
##         16        201      40495      71105
```
