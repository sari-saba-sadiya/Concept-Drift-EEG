# Concept-Drift-EEG
Concept-drift in electroencephalography data

## Algorithms 

### Drift Detection 

| _Algorithm_     | _type_          | _Implementation_ |
| --------------- | --------------- |  --------------- |
| DDM             | Error rate      | [skmultiflow.drift_detection.DDM](https://scikit-multiflow.readthedocs.io/en/latest/api/generated/skmultiflow.drift_detection.DDM.html)
| EDDM            | Error rate      | [skmultiflow.drift_detection.EDDM](https://scikit-multiflow.readthedocs.io/en/latest/api/generated/skmultiflow.drift_detection.EDDM.html)
| ADWIN           | Error rate      | [skmultiflow.drift_detection.ADWIN](https://scikit-multiflow.readthedocs.io/en/latest/api/generated/skmultiflow.drift_detection.ADWIN.html)
| HDDM            | Error rate      | [skmultiflow.drift_detection.HDDM_W](https://scikit-multiflow.readthedocs.io/en/latest/api/generated/skmultiflow.drift_detection.HDDM_W.html)


## Datasets
| _Data-set_     | _Description_    | _Comments_ | _Links_ |
| --------------- | --------------- |  --------------- | --------------- | 
| Helsinki NICU Data | Expert annotation of multi channel EEG Seizure Data | average 74 min | [ETFE 2019](https://www.mdpi.com/1099-4300/21/12/1187) |
| Synthetic Data | Missing | Same authors as [ETFE] | [FEED](https://core.ac.uk/download/pdf/185512443.pdf)
| UCI EEG eye-state | Open vs Closed | used in [MDSM](https://www.hindawi.com/journals/mpe/2015/874032/) | [UCI eeg eye-state](https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State)

## EEG Papaers
[FEDD] Cavalcante, Minku, and Oliveira (IJCNN 2016), FEDD: Feature Extraction for Explicit Concept Drift Detection in time series.

[ETFE] Fengqian Ding and Chao Luo (Entropy 2019), The Entropy-Based Time Domain Feature Extraction for Online Concept Drift Detection. [code](https://github.com/dingfengqian/ETFE)

[MDSM] Haibo et. al, (Hindawi Publishing Corporation) Adaptive Ensemble with Human Memorizing Characteristics for Data Stream Mining.

