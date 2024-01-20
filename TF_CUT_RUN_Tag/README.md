# TF CUT&RUN/Tag data processing code

## USAGE

### Install required softwares list on `README.md` files in `genome_source_build` and `pipeline` directories

### Build genome source files

```bash
genomeVersion=mm10
mkdir -p ~/source/bySpecies/${genomeVersion}/ && cd ~/source/bySpecies/${genomeVersion}/
bash /path/to/genome/source/build/build_genome_source.sh ${genomeVersion}
```

### Process TF CUT&RUN data

1. Store raw sequencing files (XX_1.fastq.gz, XX_2.fastq.gz) into `./0_raw_data/`
2. `bash CUT_RUN_TF/CUT_RUN_TF.sh sample_name processer_num mm10 XX_1.fastq.gz XX_2.fastq.gz true`

## Citation

Wang, Wen, et al. "ADNP Modulates SINE B2-Derived CTCF-Binding Sites during Blastocyst Formation in Mouse." *BioRxiv* (2023): 2023-11. https://www.biorxiv.org/content/early/2023/11/24/2023.11.24.567719
