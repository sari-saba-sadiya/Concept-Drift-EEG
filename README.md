# Concept-Drift-EEG
Concept-drift in electroencephalography data

## Algorithms 

### Drift Detection 

| _Algorithm_     | _type_          | _Implementation_ |
| --------------- | --------------- |  --------------- |
| DDM             | Error rate      | Detection/DDM.ipynb and [skmultiflow.drift_detection.DDM](https://scikit-multiflow.readthedocs.io/en/latest/api/generated/skmultiflow.drift_detection.DDM.html)
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
- [FEDD] Cavalcante, Minku, and Oliveira (IJCNN 2016), FEDD: Feature Extraction for Explicit Concept Drift Detection in time series.
- [ETFE] Fengqian Ding and Chao Luo (Entropy 2019), The Entropy-Based Time Domain Feature Extraction for Online Concept Drift Detection. [code](https://github.com/dingfengqian/ETFE)
- [MDSM] Haibo et. al, (Hindawi Publishing Corporation) Adaptive Ensemble with Human Memorizing Characteristics for Data Stream Mining.

## Papers
[LFR] : Wang, H., Abraham, Z., 2015. Concept drift detection for stream- ing data. In: International Joint Conference on Neural Networks (IJCNN). IEEE, pp. 1–9.
[DDM] : Gama, J., Medas, P., Castillo, G., Rodrigues, P., 2004. Learning with drift detection. In: Advances in artificial intelligence–SBIA 2004. Springer, pp. 286–295.
[EDDM] : Baena-Garcıa, M., del Campo-A ́vila, J., Fidalgo, R., Bifet, A., Gavalda, R., Morales-Bueno, R., 2006. Early drift detection method. In: Fourth international workshop on knowledge discov- ery from data streams. Vol. 6. pp. 77–86.
[ADWIN] :  Bifet, A., Gavalda, R., 2007. Learning from time-changing data with adaptive windowing. In: SDM. Vol. 7. SIAM
[Resampling] : Harel, M., Mannor, S., El-Yaniv, R., Crammer, K., 2014. Concept drift detection through resampling. In: Proceedings of the 31st Inter- national Conference on Machine Learning (ICML-14). pp. 1009– 1017.
[OLINDDA] : Spinosa, E. J., de Leon F de Carvalho, A. P., Gama, J., 2007. Olindda: A cluster-based approach for detecting novelty and concept drift in data streams. In: Proceedings of the 2007 ACM symposium on Applied computing. ACM, pp. 448–452.
[MINAS] : Faria, E. R., Gama, J., Carvalho, A. C., 2013. Novelty detection algorithm for data streams multi-class problems. In: Proceedings of the 28th Annual ACM Symposium on Applied Computing. ACM, pp. 795–800.
[DETECTNOD] : Hayat, M. Z., Hashemi, M. R., 2010. A dct based approach for detecting novelty and concept drift in data streams. In: International Conference of Soft Computing and Pattern Recognition (SoCPaR). IEEE, pp. 373–378.
[Woo-ensemble] : Ryu, J. W., Kantardzic, M. M., Kim, M.-W., Khil, A. R., 2012. An efficient method of building an ensemble of classifiers in streaming data. In: Big data analytics. Springer, pp. 122–133.
[ECSMiner] : Masud, M. M., Gao, J., Khan, L., Han, J., Thuraisingham, B., 2011. Classification and novel class detection in concept-drifting data streams under time constraints. IEEE TKDE 23 (6), 859–874.
[GC3] : Sethi, T. S., Kantardzic, M., Hu, H., 2016b. A grid density based framework for classifying streaming data in the presence of concept drift. Journal of Intelligent Information Systems 46 (1), 179– 211.
[CoC] : Lee, J., Magoules, F., 2012. Detection of concept drift for learn- ing from stream data. In: IEEE 14th International Conference on High Performance Computing and Communication & 2012 IEEE 9th International Conference on Embedded Software and Systems (HPCC-ICESS). IEEE, pp. 241–245.
[HDDDM] : Ditzler, G., Polikar, R., 2011. Hellinger distance based drift detection for nonstationary environments. In: IEEE Symposium on Com- putational Intelligence in Dynamic and Uncertain Environments (CIDUE). IEEE, pp. 41–48.
[PCA-1] : Kuncheva, L. I., Faithfull, W. J., 2014. Pca feature extraction for change detection in multidimensional unlabeled data. IEEE Transactions on Neural Networks and Learning Systems 25 (1), 69–80.
[PCA-2] : Qahtan, A. A., Alharbi, B., Wang, S., Zhang, X., 2015. A pca-based change detection framework for multidimensional data streams: Change detection in multidimensional data streams. In: Proc. of the 21th ACM SIGKDD ICKDDM. ACM, pp. 935–944.
[A-distance]: D. Kifer, S. Ben-David, and J. Gehrke, “Detecting change in data streams,” in Proc. 30th Int. Conf. Very Large Data Bases, 2004, vol. 30, pp. 180–191. 
[margin] : Dries, A., Ruckert, U., 2009. Adaptive concept drift detection. Statistical Analysis and Data Mining 2 (5-6), 311–327.
[MD3]: Sethi, T. S., Kantardzic, M., 2017. On the reliable detection of concept drift from streaming unlabeled data. Expert Syst. Appl. 82, C (October 2017), 77-99. DOI: https://doi.org/10.1016/j.eswa.2017.04.008
[sampling]: C. C. Aggarwal, “On biased reservoir sampling in the presence of stream evolution,” in Proc. 32nd Int. Conf. Very Large Data Bases, 2006, pp. 607–618.
[JIT]: C. Alippi, G. Boracchi, and M. Roveri, “A just-in-time adaptive classification system based on the intersection of confidence intervals rule,” Neural Netw., vol. 24, no. 8, pp. 791–800, Oct. 2011.
[ONSboost] : A. Pocock, P. Yiapanis, J. Singer, M. Lujan, and G. Brown, “Online nonstationary boosting,” in Proc. Int. Workshop Multiple Classifier Systems, 2010, pp. 205–214.
[NSRF] : H. Abdulsalam, D. Skillicorn, and P. Martin, “Classification using streaming random forests,” IEEE Trans. Knowledge Data Eng., vol. 23, no. 1, pp. 22–36, Jan. 2011.
[DWM] : J. Kolter and M. Maloof, “Dynamic weighted majority: An ensemble method for drifting concepts,” J. Mach. Learn. Res., vol. 8, pp. 2755–2790, Dec. 2007
[Learn++.NSE] : R. Elwell and R. Polikar, “Incremental learning of concept drift in nonstationary environments,” IEEE Trans. Neural Netw., vol. 22, no. 10, pp. 1517–1531, Oct. 2011.
