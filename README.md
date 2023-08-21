# Network-intrusion-detection-with-machine-learning
Ce projet, réalisé dans le cadre de mon travail de bachelor à la Haute École de Gestion de Genève, se concentre sur l'utilisation du deep learning pour la détection d'intrusions réseau.

## Description
Ce travail vise à développer un système de détection d'intrusions réseau en utilisant des techniques de deep learning. Le dataset UNSW-NB15 a été utilisé comme source de données, et le framework Keras a été choisi pour l'implémentation du modèle. Le modèle de réseau de neurones à convolution (CNN) a été particulièrement exploité pour identifier le type d'infraction réseau.

## Prérequis
- Télécharger le dataset UNSW-NB15 : https://research.unsw.edu.au/projects/unsw-nb15-dataset
- Google Colab (ou autre): https://colab.research.google.com/

## Organisation du projet
- prepare_data_CNN.ipynb: Ce notebook prépare les données pour l'entraînement du modèle et crée un CSV pour l'entraînement.
- CNN_Multiclass.ipynb: Ce notebook explore et compare différentes architectures de CNN.
- all_data_UNSW-NB15.csv: Ce fichier CSV transformé par prepare_data_CNN.ipynb est prêt à l'emploi.
- entrainement/: Ce dossier contient divers essais pour comprendre le fonctionnement de Keras, basés sur des ressources existantes (repris de githubs cités en dessous).

## Plus d'informations
Pour plus d'informations, vous pouvez consulter le rapport de travail de bachelor (en français) disponible dans ce repository.

## Citations
Ces citations sont obligatoires pour l'utilisation du dataset UNSW-NB15.
- Moustafa, Nour, and Jill Slay. "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)." Military Communications and Information Systems Conference (MilCIS), 2015. IEEE, 2015.
- Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset." Information Security Journal: A Global Perspective (2016): 1-14.
- Moustafa, Nour, et al. "Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks." IEEE Transactions on Big Data (2017).
- Moustafa, Nour, et al. "Big data analytics for intrusion detection system: statistical decision-making using finite dirichlet mixture models." Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. 127-156.
- Sarhan, Mohanad, Siamak Layeghy, Nour Moustafa, and Marius Portmann. NetFlow Datasets for Machine Learning-Based Network Intrusion Detection Systems. In Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020, Virtual Event, December 11, 2020, Proceedings (p. 117). Springer Nature.

### Thank you for this github
Ce travail a été inspiré par les ressources disponibles sur GitHub. Un grand merci à leurs auteurs:

- https://github.com/SubrataMaji/IDS-UNSW-NB15/tree/master
- https://github.com/CharlesMure/cassiope-NIDS/tree/master
- https://github.com/Faridbg/CNN_UNSW-NB15/tree/master

Merci d'avoir pris le temps d'explorer ce projet. Pour toute question ou commentaire, n'hésitez pas à me contacter.

