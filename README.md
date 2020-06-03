# absoluteCNVdata

Pre-compiled absolute CNV data, which can be used for package [sigminer](https://github.com/ShixiangWang/VSHunter) (examples or data mining) and related CNV analysis.

`.rda` and `.RData` file can read with `load()` function, `.rds` file can read with `readRDS()` function.

### TCGA pancan ABSOLUTE calling results

Generate from Synapse, paper link https://www.nature.com/articles/nbt.2203

* pancan12_absolute.rda
* pancan12_info.rda

### CNV signature results from BriTROC-1 study

Generate from https://www.nature.com/articles/s41588-018-0179-8

* example_cn_QDNASeq.RData
* component_parameters.rds
* NatGen_features.rda

### Chromosome size of hg19 and hg38

* hg19.chrom.sizes.txt
* hg38.chrom.sizes.txt

## Citation

_Wang, Shixiang, et al. "APOBEC3B and APOBEC mutational signature as potential predictive markers for immunotherapy response in non-small cell lung cancer." Oncogene (2018)._

## Reference

* Carter, S. L., Cibulskis, K., Helman, E., McKenna, A., Shen, H., Zack, T., ... & Beroukhim, R. (2012). Absolute quantification of somatic DNA alterations in human cancer. Nature biotechnology, 30(5), 413.
* Macintyre, G., Goranova, T. E., De Silva, D., Ennis, D., Piskorz, A. M., Eldridge, M., ... & Dowson, S. (2018). Copy number signatures and mutational processes in ovarian carcinoma. Nature genetics, 50(9), 1262-1270.
