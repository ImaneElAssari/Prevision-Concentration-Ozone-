# Prevision-Concentration-Ozone-
Ce notebook est à l’origine un TP du cours « Découvrez la science des données pour les objets connectées ».  Il a pour objet la prévision de la concentration d’Ozone à base d’une prévision déterministe sur un maillage grossier et des variables bioclimatiques relatives aux stations étudiées.

L’analyse de forme nous a permis d’explorer en gros la dataset qui comporte 10 colonnes et 1041 enregistrements. Notre Target est la variable O3obs.
Afin de mieux avoir une idée sur nos données on a  effectué une analyse exploratoire uni et bidimensionnelle. L’utilisation de l’analyse en composantes principales nous a bien permis d’avoir une idée précise sur la structure des données.

Pour la modélisation, on a opté pour le K-NN et le perceptron multicouche MLP au niveau des modèles simples(Singles), ensuite on a utilisé le Random Forest et XGBoost comme modèles ensemblistes. L’utilisation de GridSearch a bien facilité le tunning des hyper paramètres.  
L’évaluation des modèles cités auparavant est réalisée en utilisant les Courbes ROC.

