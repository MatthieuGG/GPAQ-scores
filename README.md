# How to obtain MET-minutes/week using GPAQ scores

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13895456.svg)](https://doi.org/10.5281/zenodo.13895456)


Run the soft from terminal using ```python3 gpaq.py [-d input_path] [-o output_path] [-ind]```  

- `[-d]` optional, defines the path to your data. Default is [~/data/](https://github.com/MatthieuGG/GPAQ-scores/tree/main/data) in the same folder.  
- `[-o]` optional, defines the path to your results. Default is [~/results/](https://github.com/MatthieuGG/GPAQ-scores/tree/main/results) in the same folder.  
- `[-ind]` optional, saves individual files. Default is [one concatenated file](https://github.com/MatthieuGG/GPAQ-scores/blob/main/results/concatenated_data.csv).  

You first have to go in the folder where gpaq.py is located using `cd`. Exemple of use: 

```
> cd /Users/Me/Downloads/GPAQ-scores-main/  
> python3 gpaq.py -d /Users/Me/Documents/gpaq/myData/ -o /Users/Me/Documents/gpaq/myResults/ -ind
```
See more information in the [documentation]() *(not yet edited)*. We based our calculation on the [GPAQ guides](https://www.who.int/docs/default-source/ncds/ncd-surveillance/gpaq-analysis-guide.pdf) and [ONAPS recommandations](https://onaps.fr/wp-content/uploads/2020/10/Interpre%CC%81tation-GPAQ.pdf).

**To cite this work:**
> Matthieu Gallou-Guyot. (2023). GPAQ-scores. Zenodo. https://doi.org/10.5281/zenodo.10060405  

*(old version using a Jupyter Nootebook is still avaliable in [~/old/](https://github.com/MatthieuGG/GPAQ-scores/tree/main/old))*
