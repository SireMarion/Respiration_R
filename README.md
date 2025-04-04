# A propos du traitement des données de metabolisme par R.
Il s'agit d'un code R permettant de traiter les données de sortie de l'appareil de mesure d'O2.
(English version below - This is an R code for processing the output data of the O2 measuring device)

## Installation 
Le code est programmé en langage R, il nécessite différentes librairies (tidyr, dplyr, readr, readxl).

1. Télécharger le code R.
2. Vérifier que les librairies nécessaires sont bien installées sur l'ordinateur.
3. Lancer le code entier.
4. Choisir les différents fichiers que l'on veut analyser à partir de la boite de dialogue ( en une seule fois - maintient de la touche Ctrl enfoncé).
5. Choisir le fichier contenant toutes les valeurs de BL, EL, BD et END pour les différents fichiers.
Le fichier est un fichier excel sous la forme :

| File | BL | EL | BD | END | Channel 1 | Channel 2 | Channel 3 | Channel 4|
|:----:|:--:|:--:|:--:|:---:|:---------:|:---------:|:---------:|:--------:|
| Name_of_the_files_1 | BL_1 | EL_1 | BD_1 | END_1 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| Name_of_the_files_2 | BL_2 | EL_2 | BD_2 | END_2 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| Name_of_the_files_3 | BL_3 | EL_3 | BD_3 | END_3 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| ... | ... | ... | ... | ... |... | ... | ... | ... |

6. Ouvrir le fichier de sortie : Final_Slopes.xlsx.

-----------------------------------------------------------------------------------------------------------------------------

The code is programmed in R language, it requires different libraries (tidyr, dplyr, readr, readxl).

1. Download the R code.
2. Verify that the necessary libraries are installed on the computer.
3. Run the entire code.
4. Choose the different files you want to analyze from the dialog box (in one go - hold down the Ctrl key).
5. Choose the file containing all the values ​​of BL, EL, BD and END for the different files.
The file is an excel file in the form:

| File | BL | EL | BD | END | Channel 1 | Channel 2 | Channel 3 | Channel 4|
|:----:|:--:|:--:|:--:|:---:|:---------:|:---------:|:---------:|:--------:|
| Name_of_the_files_1 | BL_1 | EL_1 | BD_1 | END_1 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| Name_of_the_files_2 | BL_2 | EL_2 | BD_2 | END_2 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| Name_of_the_files_3 | BL_3 | EL_3 | BD_3 | END_3 | Name of the modality 1 |Name of the modality 2 | Name of the modality 3 | Name of the modality 4 |
| ... | ... | ... | ... | ... |... | ... | ... | ... |

6. Open the output file: Final_Slopes.xlsx.
