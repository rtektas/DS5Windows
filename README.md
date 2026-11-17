# DS5Windows
### Édition Resul Tektas · v1.0 — personnalisation

**Une configuration prête à essayer pour utiliser une manette PS5 DualSense sur PC.**

Version personnalisée par **Resul Tektas**, basée sur **DS4Windows 3.3.3**.
DS5Windows est le nom de cette distribution personnalisée. Le moteur de détection,
de configuration et d’émulation reste celui de DS4Windows.

## Télécharger

> **Publication incomplète : l’application ne peut pas encore être lancée depuis ce dépôt.** Sept fichiers binaires restent à publier. Les instructions ci-dessous seront applicables une fois le transfert terminé.

Après la publication complète, clique sur **Code → Download ZIP**, puis extrais l’archive complète.

## Démarrage rapide

1. Ferme complètement toute autre instance de DS4Windows ou DS5Windows.
2. Extrais tout le ZIP dans un nouveau dossier accessible en écriture.
3. Lance **DS5Windows.exe** dans le dossier extrait.
4. Si l’application demande où enregistrer les réglages, choisis **Program Folder**.
5. Branche la DualSense avec un câble USB-C qui transmet les données.
6. Sélectionne le profil **Resul - DualSense** et clique sur Démarrer si nécessaire.

Ouvre **BIENVENUE.html** pour la présentation personnalisée et
**GUIDE-PS5.txt** pour le Bluetooth et le dépannage.

## L’édition Resul Tektas

- Nom de distribution et exécutable de lancement : DS5Windows.
- Prise en charge DualSense activée dans la configuration livrée.
- Profil « Resul - DualSense » sélectionné pour les huit emplacements.
- Éclairage bleu cyan du profil : RGB 0,170,255.
- Interface configurée en français.
- Page d’accueil hors ligne, guide et documentation personnalisés.
- Sortie virtuelle Xbox 360 conservée pour les jeux XInput.

## Ce qu’il faut savoir

La fenêtre et certains messages internes portent encore le nom DS4Windows :
l’archive fournie contient le logiciel compilé, pas son projet source.
Les DLL, les fichiers runtime et les noms XML techniques sont conservés afin
de ne pas casser les dépendances. Le fichier EXE est renommé sans modifier
son contenu ; il référence toujours DS4Windows.dll.

Cette édition ne crée pas de nouveau pilote et ne réécrit pas le moteur.
Le mode Xbox 360 ne fournit pas les fonctions DualSense natives des jeux
(gâchettes adaptatives pilotées par le jeu, haptique avancée).

## Prérequis

- Windows x64 compatible avec le moteur fourni.
- Microsoft .NET 8 Desktop Runtime x64.
- ViGEmBus pour l’émulation Xbox 360 ; déjà présent dans les journaux du PC
  de l’archive d’origine. Aucun pilote n’est installé par ce ZIP.
- Câble USB de données ou connexion Bluetooth compatible.

## Vérifications

Archive ZIP et XML contrôlés. Le fichier EXE renommé et toutes les DLL sont
identiques à ceux de l’archive de départ. Aucun test d’exécution sous Windows
ou avec une DualSense physique n’a été effectué dans cet environnement.

## Crédits

**Personnalisation, configuration et présentation : Resul Tektas.**

**Logiciel de base : DS4Windows, Jays2Kings, Ryochan7 et contributeurs.**
Les composants tiers restent la propriété de leurs auteurs respectifs.
Cette édition n’est pas une version officielle de Sony ou de DS4Windows.
Voir **CREDITS.md** pour la distinction entre personnalisation et moteur.
