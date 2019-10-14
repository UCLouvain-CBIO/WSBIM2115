# WSBIM2115 - Relations structure/fonction des protéines

## Proteomics bioinformatics

### Mass spectrometry
- MS plays a central role for high-throughput proteomics.
- Review of how MS works.


### Peptide mass finderprinting

- Using the free [Matrix Science Mascot server](http://www.matrixscience.com/search_form_select.html)
- PMF input data

```
802.5
967.4
712.9
656.8
932.0
1186.0
818.7
1063.0
1054.5
1646.1
1195.8
1153.3
1444.0
1050.4
1596.0
2193.0
1197.7
1834.2
2012.4
1228.3
2505.6
1328.7
2272.8
```

### MSMS search

- Download the input data (in [mgf
  format](http://www.matrixscience.com/help/data_file_help.html)) and
  familiarise yourself with it.
- Plot one of these MSMS spectra
- Run an MSMS search using the free [Matrix Science Mascot
  server](http://www.matrixscience.com/search_form_select.html)
- Interprete the results. Use the following
  [data](./test.mgf).
- Use the following search parameters: Instrument *ESI-TRAP*, variable
  modification *oxidation*, search databases *contaminants and
  SwissProt*, enzyme *Trypsin* with up to 1 mis-cleavage, taxonomy
  *Homo sapiens*.
- Repeat the search without taxonomic group.

###

Find and download the PKA sequences for the human, fly, chicken,
xenophus, ... (and possibly a couple of other ones)



PKA structures
- https://www.ncbi.nlm.nih.gov/Structure/mmdb/mmdbsrv.cgi?uid=71781
- https://www.ncbi.nlm.nih.gov/Structure/mmdb/mmdbsrv.cgi?uid=71583