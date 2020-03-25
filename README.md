# sc-methods-eval
Notes and code for evaluation of single cell processing tools

### Tools to evaluate

* [STARsolo](https://github.com/alexdobin/STAR/blob/master/docs/STARsolo.md) from Alex, the author or STAR.
* [Kallisto + bustools](https://www.kallistobus.tools/), a python wrapper [kb-python](https://github.com/pachterlab/kb_python) can be handy but the error messages are not that informative in my experience. Read the preprint: [Modular and efficient pre-processing of single-cell RNA-seq](https://www.biorxiv.org/content/10.1101/673285v1)
* [Salmon + Alevin](https://salmon.readthedocs.io/en/latest/alevin.html) read the preprint: [Preprocessing choices affect RNA velocity results for droplet scRNA-seq data](https://www.biorxiv.org/content/10.1101/2020.03.13.990069v1.full.pdf). It support single-nuclei data now!


### Runs for benchmarking
(cellranger count times), source data location: /n/boslfs02/LABS/informatics/sequencing/source/

* 191218_A00794_0145_AH2G23DSXY - S4 Novaseq (90 samples,  we didn't finish count for this one, just delivered fastq)

* 200227_A00794_0189_BH2JF2DSXY - S4 Novaseq (54 samples, approx 20hrs)

* 200316_A00794_0205_AHN3N3DMXX - S2 Novaseq (7.5 hrs x 4 samples, 14 hrs x 1 sample, 13 hrs x 1 sample)

* 200306_NB551608_0159_AHNNVKBGXC - Nextseq 1 sample (5 hrs)

* 200316_D00742_0363_BHCVK3BCX3 - HiSeq 3 samples (3 hrs x 2 samples, 1 hr x 1 sample)
