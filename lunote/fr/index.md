---
layout: default
title: LuNote Manual (FR)
---

---
Disposition: par défaut
Titre: Manuel Lunote
---

# Manuel de l'utilisateur Lunote

> Dernier mis à jour: {{site.time | Date: '% y-% m-% d'}}

Bienvenue à ** Lunote **, votre journal tout-en-un, le todo et le compagnon de logage de vie. Ce guide se concentre sur les commandes de l'écran principal - ce qui se passe lorsque vous appuyez sur, double-vous ou à longue pression - et donne un aperçu de chaque fonctionnalité principale afin que vous puissiez tirer le meilleur parti de l'application.

## 1. Écran d'accueil en un coup d'œil

| Zone | But |
| ------ | --------- |
| ** barre de date ** | Montre la date d'aujourd'hui. Appuyez pour ouvrir le cueilleur de calendrier et sautez à n'importe quelle date. |
| ** CARTES ** | Widgets rapides pour * aujourd'hui intime * Aperçu, * J-Day * Countdown et * étape * Résumé. |
| ** Navigation inférieure ** | Cinq onglets pour le journal, le TODO, le jour J, les statistiques et les paramètres. |
| ** Bouton d'action flottante (+) ** | Créez de nouvelles entrées de n'importe où. |

## 2. Boutons de navigation inférieure

| Bouton | Tap unique | Double Tap | Longue presse |
| -------- | ----------- | ----------- | ------------ |
| ** Journal ** | Ouvrez la liste des journaux pour la date sélectionnée | Faites défiler en haut de la liste | Picker à date ouverte |
| ** TODO ** | Togle * Aujourd'hui * ⇄ * Demain * Liste | Effondrement / expansser * aujourd'hui * Section | Marquez tous les todos complets / incomplets |
| ** J-Day ** | Afficher les minuteries à rebours | Sautez l'événement à venir le plus proche | Options de tri / filtre |
| ** Statistiques ** | Ouvert des statistiques principales Hub | Plage de cycle * 7 → 30 → 90 * jours | Exporter le graphique de courant comme CSV |
| ** Paramètres ** | Préférences ouvertes | - | Afficher les informations de l'application |

## 3. Bouton d'action flottante (+)

| Geste | Action |
| --------- | -------- |
| Appuyez | Choisissez * Journal * / * TODO * / * J-Day * Type d'entrée |
| Double-Tap | Entrée immédiate de la diaryde |
| Longue presse | Commande vocale (bêta) |

## 4. Icônes de la barre d'application et de l'outil

| Icône | Action |
| ------ | -------- |
| 🔍 ** Recherche ** | Recherche globale à travers le journal, le TODO et le jour J |
| 🔄 ** sync ** | Invite de sauvegarde / restauration du cloud manuel |
| 🔔 ** Alerte minuit ** | Bascule 00:00 Rappel quotidien |
| 📊 ** Envoyer aux statistiques ** | Poussez les données actuelles vers le module statistique |
| ⋮ ** Plus de menu ** | Exportation / importation • Suivi GPS • Comparaison de distance • Modèle d'activité • ** Gestion de la base de données ** • ** Manuel d'utilisation ** |

## 5. gestes partout

- ** Swipe à gauche ** → Supprimer l'élément actuel
- ** Swipe à droite ** → Modifier l'élément
- ** Pince ** → Ajuster la taille du texte à la volée
- ** Shake ** → Toggle Dark Mode

## 6. Tableau de bord statistiques

Consulté via l'onglet ** Stats **, le tableau de bord offre plusieurs pages:

| Page | Widgets et outils |
| ------ | ----------------- |
| ** Statistiques du journal ** | Fréquence d'entrée carte thermique, mot-clé cloud, graphique à tarte à l'humeur |
| ** Counter de pas ** | Estimations quotidiennes du tableau des lignes, distance et calories |
| ** Modèle d'activité ** | Histogramme d'heure par heure, rapport actif / inactif |
| ** Comparaison de distance ** | Bar Graphique comparant la marche vs courir vs cyclisme |
| ** Carte quotidienne de l'itinéraire ** | La superposition de cartographie des traces GPS (nécessite une autorisation de localisation) |
| ** Météo et lune ** | Tendances météorologiques et widgets de phase de lune |

Chaque graphique prend en charge: * Zoom / Pan * avec pincement, * commutateur de plage * (double-tap) et ** Export ** comme png / csv / pdf via le menu supérieur-droit ⋮.

## 7. Sauvegarde et restauration

1. Ouvrez ** Paramètres ▸ Sauvegarde / restauration **.
2. Connectez-vous à Google Drive (première fois uniquement).
3. Appuyez sur ** Sauvegarde maintenant ** pour télécharger JSON + SQLITE Snapshot.
4. Pour restaurer, choisissez une sauvegarde et appuyez sur ** restaurer **.

## 8. FAQ

** Pourquoi les publicités ne sont-elles pas affichées? **  
Les annonces peuvent être vides jusqu'à 48 h après une nouvelle sortie de magasin. Pour vérifier l'intégration, activez ** Test Ads ** dans * Paramètres ▸ Debug *.

** iCloud / Drive Sync est coincé? **  
Connectez-vous du compte Cloud et reconnez, puis réessayez.

## 9. Support

- Courriel: [support@lunote.app] (mailto: support@lunote.app)
- Problèmes de github: <https://github.com/schaam/lunote/issues>

---
Fabriqué avec ❤️ par l'équipe ** Lunote **