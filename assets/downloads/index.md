---
layout: default
title: Catàleg de scripts descarregables
---

# Catàleg de scripts descarregables

Aquest catàleg organitza les eines del Servei de Bioinformàtica de forma clara: cada fitxer té una **breu explicació**, el **cas d'ús** i l'**enllaç de descàrrega directa**.

## Índex ràpid

### Python
- [template_scanpy.py](#template_scanpypy)
- [scRNA preprocess.ipynb](#scrna-preprocessipynb)
- [InferGRN.ipynb](#infergrnipynb)
- [pyBoost.ipynb](#pyboostipynb)
- [Pycistarget.ipynb](#pycistargetipynb)
- [pycistopic.ipynb](#pycistopicipynb)
- [Scenicplus workflow.ipynb](#scenicplus-workflowipynb)
- [Ridge anar provant.ipynb](#ridge-anar-provantipynb)

### R
- [template_seurat.R](#template_seuratr)
- [kallisto_to_counts.R](#kallisto_to_countsr)
- [combat-seq (1).R](#combat-seq-1r)
- [combat-seq (2).R](#combat-seq-2r)
- [enrich_anl_CD4 (1).Rmd](#enrich_anl_cd4-1rmd)
- [scATACseqOpenProblems.Rmd](#scatacseqopenproblemsrmd)
- [TI_anl_CD4 (1).Rmd](#ti_anl_cd4-1rmd)
- [Preprocess (1).Rmd](#preprocess-1rmd)
- [regulon.Rmd](#regulonrmd)

### Altres formats
- [template_hpc_job.sh](#template_hpc_jobsh)
- [InferGRN.sh](#infergrnsh)
- [fastcormics_in.m](#fastcormics_inm)

---

## Python

### `template_scanpy.py`
**Què fa:** plantilla base per iniciar un pipeline d'anàlisi single-cell RNA-seq amb Scanpy.  
**Per a què serveix:** punt de partida ràpid per estandarditzar pre-processat i passos inicials en Python.  
**Descarrega:** [template_scanpy.py](./scripts/template_scanpy.py)

### `scRNA preprocess.ipynb`
**Què fa:** notebook de pre-processament de dades scRNA.  
**Per a què serveix:** revisar un flux complet de neteja, normalització i preparació de dades abans de l'anàlisi.  
**Descarrega:** [scRNA preprocess.ipynb](./scripts/scRNA%20preprocess.ipynb)

### `InferGRN.ipynb`
**Què fa:** notebook orientat a la inferència de xarxes reguladores gèniques (GRN).  
**Per a què serveix:** provar fluxos d'inferència de regulació gènica a partir de dades d'expressió.  
**Descarrega:** [InferGRN.ipynb](./scripts/InferGRN.ipynb)

### `pyBoost.ipynb`
**Què fa:** notebook per experimentar amb mètodes de boosting en context bioinformàtic.  
**Per a què serveix:** prototipar models predictius i comparar rendiment.  
**Descarrega:** [pyBoost.ipynb](./scripts/pyBoost.ipynb)

### `Pycistarget.ipynb`
**Què fa:** notebook per executar anàlisi de motifs i enrichments amb pycistarget.  
**Per a què serveix:** identificar reguladors potencials i elements reguladors associats.  
**Descarrega:** [Pycistarget.ipynb](./scripts/Pycistarget.ipynb)

### `pycistopic.ipynb`
**Què fa:** notebook de treball amb pycisTopic per dades scATAC-seq.  
**Per a què serveix:** explorar temes/accessibilitat cromatínica i generar representacions útils per anàlisi downstream.  
**Descarrega:** [pycistopic.ipynb](./scripts/pycistopic.ipynb)

### `Scenicplus workflow.ipynb`
**Què fa:** workflow de SCENIC+ per integració reguladora.  
**Per a què serveix:** construir i interpretar xarxes reguladores enriquides amb informació multi-òmica.  
**Descarrega:** [Scenicplus workflow.ipynb](./scripts/Scenicplus%20workflow.ipynb)

### `Ridge anar provant.ipynb`
**Què fa:** notebook d'experiments amb regressió Ridge.  
**Per a què serveix:** fer proves ràpides de modelització regularitzada sobre dades de recerca.  
**Descarrega:** [Ridge anar provant.ipynb](./scripts/Ridge%20anar%20provant.ipynb)

---

## R

### `template_seurat.R`
**Què fa:** plantilla base per anàlisi single-cell RNA-seq amb Seurat.  
**Per a què serveix:** començar projectes de manera consistent i reutilitzable en entorn R.  
**Descarrega:** [template_seurat.R](./scripts/template_seurat.R)

### `kallisto_to_counts.R`
**Què fa:** transforma/organitza sortides de kallisto cap a matrius de counts útils per anàlisi posterior.  
**Per a què serveix:** preparar resultats de quantificació per workflows d'expressió diferencial i QC.  
**Descarrega:** [kallisto_to_counts.R](./scripts/kallisto_to_counts.R)

### `combat-seq (1).R`
**Què fa:** script per aplicar estratègies de correcció d'efecte batch amb ComBat-seq.  
**Per a què serveix:** reduir biaixos tècnics entre lots de mostres.  
**Descarrega:** [combat-seq (1).R](./scripts/combat-seq%20%281%29.R)

### `combat-seq (2).R`
**Què fa:** variant/addicional del flux ComBat-seq.  
**Per a què serveix:** comparar o adaptar configuracions de correcció batch segons el dataset.  
**Descarrega:** [combat-seq (2).R](./scripts/combat-seq%20%282%29.R)

### `enrich_anl_CD4 (1).Rmd`
**Què fa:** anàlisi d'enriquiment funcional en context CD4.  
**Per a què serveix:** interpretar llistes de gens en termes de vies, funcions i signatures biològiques.  
**Descarrega:** [enrich_anl_CD4 (1).Rmd](./scripts/enrich_anl_CD4%20%281%29.Rmd)

### `scATACseqOpenProblems.Rmd`
**Què fa:** notebook RMarkdown amb exploració/problemes oberts de scATAC-seq.  
**Per a què serveix:** documentar hipòtesis, reptes metodològics i possibles solucions d'anàlisi.  
**Descarrega:** [scATACseqOpenProblems.Rmd](./scripts/scATACseqOpenProblems.Rmd)

### `TI_anl_CD4 (1).Rmd`
**Què fa:** anàlisi d'inferència de trajectòries (trajectory inference) per dades CD4.  
**Per a què serveix:** estudiar transicions cel·lulars i dinàmiques de diferenciació.  
**Descarrega:** [TI_anl_CD4 (1).Rmd](./scripts/TI_anl_CD4%20%281%29.Rmd)

### `Preprocess (1).Rmd`
**Què fa:** notebook de pre-processament en R.  
**Per a què serveix:** deixar una traça reproduïble del pipeline inicial de neteja i preparació de dades.  
**Descarrega:** [Preprocess (1).Rmd](./scripts/Preprocess%20%281%29.Rmd)

### `regulon.Rmd`
**Què fa:** notebook per anàlisi de regulons.  
**Per a què serveix:** identificar programes reguladors i patrons de control transcripcional.  
**Descarrega:** [regulon.Rmd](./scripts/regulon.Rmd)

---

## Altres formats

### `template_hpc_job.sh`
**Què fa:** plantilla de script de llançament de job per clúster HPC.  
**Per a què serveix:** estandarditzar enviament de feines i recursos en entorns de computació d'alt rendiment.  
**Descarrega:** [template_hpc_job.sh](./scripts/template_hpc_job.sh)

### `InferGRN.sh`
**Què fa:** script shell per automatitzar part d'un flux d'inferència de GRN.  
**Per a què serveix:** executar passos repetitius de pipeline des de terminal/HPC.  
**Descarrega:** [InferGRN.sh](./scripts/InferGRN.sh)

### `fastcormics_in.m`
**Què fa:** script en MATLAB associat a fluxos Fastcormics.  
**Per a què serveix:** preparar o executar mòduls específics del workflow en aquest entorn.  
**Descarrega:** [fastcormics_in.m](./scripts/fastcormics_in.m)

---

> Nota: Si actualitzeu fitxers, manteniu aquesta estructura (descripció + utilitat + descàrrega) per conservar el catàleg net i fàcil de navegar.
