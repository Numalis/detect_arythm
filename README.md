# detect_arythm

## description des fichiers disponibles
* models.zip: dossier contenant deux modèles:
  * model_cnn_detect_arythm_2d.onnx: modele prenant en entrée l'input *x_test_0.jpg*
  * model_cnn_detect_arythm.onnx: modele prenant en entrée l'input *ts_0_0.csv*   

## decription du jeu de donnees
Les deux jeux de données contiennent 188 colonnes dont la derniere colonne indique l'appartenance aux cinq classes suivantes: (todo associer une image pour chaque classe)

* Classe 0: rythme non ectopiques normal
* Classe 1: rythme ectopiques supraventriculaires
* Classe 2: rythme ectopiques ventriculaire
* Classe 3: rythme de fusion
* Classe 4: rythme inconnus


