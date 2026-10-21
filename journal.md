# Log de développement #
Après beaucoup de pratique avec le template, où j'ai exploré, modifié etc. avec Codex et ChatGPT le template, j'ai tout effacé et recommencé afin de faire mon site web selon les règles de l'art. Je pense notamment à mes commits -m qui étaient vraiment pas spécifique, à des modifications que j'ai fait que j'ai pas compris. Ce fichier .md va servir de log pour les vagues de modification. 
Note : ChatGPT n'a servi qu'au brainstorm et j'ai utilisé Codex pour m'aider à localiser les règles du main.css. 
# Brainstorm #
Je veux un site web...
## Design 
- Style académique 
- Noir et blanc (monochrome)
- Que la sidebar reste collapsable même en grand écran et que la bannière du top reste. -> J'ai rien compris de comment faire ça. 
- Pas de grosse image de background mais une photo de moi à côté du texte. 
- Police d'écriture 
   - Cormorant Garamond pour les headers 
   - IBM Plex Sans pour paragraphes
   - IBM Plex mono pour petits labels et notes
Couleurs : 
- Blanc (#FFFFFF) pour le fond 
- Noir (#111111) pour le texte. 
## Structure : 
- Site web d'une seule page avec sections : 
   - Introduction (À propos) : un petit texte pré-écrit. 
   - Intérêts de recherche : Une section Intérêts de recherche avec : Extrémisme de droite ; Nationalisme ; Violence politique ; Politique québécoise ; Analyses discursives 
   - Compétences : avec icones : Livre : Recherche (recherche documentaire et bibliographie ; Revue de littérature), Ordi : Outils numériques (R, Git, Obsidian, Zotero, Adobe Creative Cloud) ; Loupe : Méthodes (Analyse qualitative ; Analyses quantitatives) ; Langues : Langues (français, anglais, allemand). 
   - CV : avec onglet quarto pour le pdf. 
   - Comment me joindre avec trois boutons : Linkedin, Facebook, Email. 
   - Side pannel : pas de photo, juste « Navigation» avec boutons vers chaque section + icones de réseaux sociaux. 
# Vagues de modification : 
## 1. Style
1) Importer les polices d'écriture Cormorant Garamond, IBM Plex Sans et IBM Plex mono de google fonts. 
2) Trouver les règles et remplacer les polices d'écriture et leur couleur (Noir : #111111, Blanc : #FFFFFF, Gris : #666666) 
3) Changer les couleurs de la page principale vers le blanc. 
4) Changer la couleur des lignes séparatrices. 
5) Importer les icones correspondants pour la section compétence. Changer leur couleur 
6) Changer la couleur des boutons
7) Créer une nouvelle règle pour la photo en noir et blanc. 
### Révisions 
Ici je marque les problèmes survenus après le push et le diagnostic. 
 1) Boutons, side pannel toujours colorés. 
 2) les lignes séparatrices sont devenus blanche
 3) La bannière au dessus demeure noire. 
Tout réparé
## 2. Structure 
1) Enlever la grosse image de background. 
2) Ajouter le portrait de moi à côté du premier paragraphe. 
3) Remplacer le titre des sections
4) Ajouter la section intérêt de recherche entre intro et mes compétences. 
5) Ajouter les trois boutons dans me joindre. 
6) Faire correspondre bouton du side pannel avec bonnes sections. 
7) Ajouter cv imbedded dans la section CV avec quarto. 
### Révisions
## 3. Contenu 
1) Remplacer les informations et le contenu. 
2) Changer le dessus du site pannel pour juste *Navigation* 
3) Lier les boutons contact aux bonnes affaires. 
### Révisions 
Ici je marque les problèmes survenus après le push et le diagnostic. 
## Modifications pour la deuxième version 
Des trucs que je suis pas à l'aise de faire encore : 
1) Faire en sorte que le side pannel demeure toujours collapsable 
2) Faire en sorte que la bannière au dessus demeure toujours. Avoir des boutons la aussi vers les sections. 
3) Avoir une section ou je présente un projet du bacc (pdf) ou code R. 
4) Avoir un bouton qui switch anglais français. 

