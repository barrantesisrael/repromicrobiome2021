### Protocol settings

`uclust` refers to the default version that comes with `qiime1` (1.2.22q); in all cases [`vsearch 2.15.2`](https://github.com/torognes/vsearch) was used instead of USEARCH61.


| algorithm | database | pipeline settings | snakefile | strand rev | folder |
| --- | --- | --- | --- | --- | --- | 
| uclust | Greengenes 13.8  | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138/Snakefile) | yes | [`uclust_gg138`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_gg138) |
| uclust (default settings) | Greengenes 13.8 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138_def/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138_def/Snakefile) | no | [`uclust_gg138_def`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_gg138_def) |
| uclust | Greengenes 13.8  | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138_norev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_gg138_norev/Snakefile) | no | [`uclust_gg138_norev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_gg138_norev) |
| uclust (default settings) | SILVA 119 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_def/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_def/Snakefile)  | no | [`uclust_silva119_def`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_silva119_def) |
| uclust | SILVA 119 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_norev/otu_SILVA_settings.txt) |  [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_norev/Snakefile) | no | [`uclust_silva119_norev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_silva119_norev) |
| uclust | SILVA 119 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_rev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva119_rev/Snakefile) | yes | [`uclust_silva119_rev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_silva119_rev) |
| uclust  | SILVA 132 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva132_norev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva132_norev/Snakefile) | no | [`uclust_silva132_norev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_silva132_norev) |
| uclust  | SILVA 132 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva132_rev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/uclust_silva132_rev/Snakefile) | yes | [`uclust_silva132_rev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/uclust_silva132_rev) |
| usearch61 | SILVA 119 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva119_norev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva119_norev/Snakefile) | no | [`usearch61_silva119_norev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/usearch61_silva119_norev) |
| usearch61 | SILVA 119 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva119_rev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva119_rev/Snakefile) | yes | [`usearch61_silva119_rev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/usearch61_silva119_rev) |
| usearch61 | SILVA 132 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva132_norev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva132_norev/Snakefile) | no | [`usearch61_silva132_norev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/usearch61_silva132_norev) |
| usearch61 | SILVA 132 | [`otu_SILVA_settings.txt`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva132_rev/otu_SILVA_settings.txt) | [`Snakefile`](https://github.com/barrantesisrael/repromicrobiome2021/blob/main/usearch61_silva132_rev/Snakefile) | yes | [`usearch61_silva132_rev`](https://github.com/barrantesisrael/repromicrobiome2021/tree/main/usearch61_silva132_rev) |

