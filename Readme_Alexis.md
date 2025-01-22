# Projet_majeure

### CRAFT

CRAFT permet de repérer les zones où se trouvent des caractères (lettres/chiffres) sur une image.

Commande pour lancer la détection de caractères avec CRAFT :

python test.py --trained_model=craft_ic15_20k.pth --test_folder=D:\Documents\COURS\ProjetMajeur\Projet_majeure\Img --cuda==false

ligne de commande final : python.exe test.py --text_threshold 0.1 --low_text 0.4 --link_threshold 0.1 --trained_model craft_mlt_25k.pth

Les résultats sont stockés dans le dossier result (Mask, Detection, Positions).
test.py