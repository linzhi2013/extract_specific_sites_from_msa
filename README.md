# extract_specific_sites_from_msa

## 1 Introduction

`extract_specific_sites_from_msa` is a tool to extract some sites (or codon) from a multiple sequence alignment.

## 2 Installation

    pip install extract_specific_sites_from_msa

There will be a command `extract_specific_sites_from_msa` created under the same directory as your `pip` command.

## 3 Usage

    usage: extract_specific_sites_from_msa [-h] [-infile <file>]
                                              [-format {fasta,emboss,stockholm,phylip,phylip-relaxed,clustal}]
                                              [-outformat {fasta,emboss,stockholm,phylip,phylip-relaxed,clustal}]
                                              [-outfile <file>] [-config <file>]
                                              [-codon <int>]

    To extract some sites (or codon) from a multiple sequence alignment. By
    Guanliang MENG, go to https://github.com/linzhi2013 for more details.

    optional arguments:
      -h, --help            show this help message and exit
      -infile <file>        input multiple sequence alignment file
      -format {fasta,emboss,stockholm,phylip,phylip-relaxed,clustal}
                            input file format [phylip-relaxed]
      -outformat {fasta,emboss,stockholm,phylip,phylip-relaxed,clustal}
                            output file format [fasta]
      -outfile <file>       outfile
      -config <file>        a file containing the sites to be extracted (1 left-
                            based). do not support 2-5, you should write 2 3 4 5
                            instead, the site numbers in config can be on one line
                            or or multiple lines.
      -codon <int>          codon site to be extracted [2]

## Author
Guanliang MENG

## Citation
Currently I have no plan to publish `extract_specific_sites_from_msa`.







