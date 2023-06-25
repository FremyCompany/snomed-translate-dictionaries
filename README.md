# snomed-translate-dictionaries
**Parallel corpus built with SNOMED CT** (by using LaBSE for candidate matching).

The current iteration provides parallel corpuses for concepts for which at least one official translation exsits, in any of the following languages:

- **Spanish** (`es`): 
  - [preview](snomed_all_en_es_map.txt.shuf.txt.4k.txt)
  or [download](snomed_all_en_es_map.txt.shuf.gz)
- **French** (`fr`)
  - [preview](snomed_all_en_fr_map.txt.shuf.txt.4k.txt) or [download](snomed_all_en_fr_map.txt.shuf.gz)
- **Dutch** (`nl`)
  - [preview](snomed_all_en_nl_map.txt.shuf.txt.4k.txt) or [download](snomed_all_en_nl_map.txt.shuf.gz)
- **Danish** (`da`)
  - [preview](snomed_all_en_da_map.txt.shuf.txt.4k.txt) or [download](snomed_all_en_da_map.txt.shuf.gz)
- **Swedish** (`sv`)
  - [preview](snomed_all_en_sv_map.txt.shuf.txt.4k.txt) or [download](snomed_all_en_sv_map.txt.shuf.gz)

The usage of these files is subject to the SNOMED licensing restrictions, see `LICENSE.txt`.

## Citation

If you use this dataset for a scientific work, please cite the following work
```bibtex
@inproceedings{remy-etal-2022-translating,
  title        = {{Taming large lexicons : translating clinical text using medical ontologies and sentence templates}},
  author       = {Remy, François and De Jaeger, Peter and Demuynck, Kris},
  booktitle    = {{EmP : 1st RADar conference on Engineer meets Physician, Proceedings}},
  location     = {{Roeselare, Belgium}},
  year         = {{2022}},
  pages        = {{5}},
  url          = {http://hdl.handle.net/1854/LU-01GMN7J3X37CKWCKQV6DWGM4ZE}
}
```
