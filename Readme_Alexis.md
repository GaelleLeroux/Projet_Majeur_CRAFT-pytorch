# Projet_majeure

### CRAFT

CRAFT permet de repérer les zones où se trouvent des caractères (lettres/chiffres) sur une image.

Commande pour lancer la détection de caractères avec CRAFT :

python test.py --trained_model=craft_ic15_20k.pth --test_folder=D:\Documents\COURS\ProjetMajeur\Projet_majeure\Img --cuda==false

Les résultats sont stockés dans le dossier result (Mask, Detection, Positions).
test.py