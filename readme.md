# Projet Openclassrooms - La Chouette Agence - Amélioré
## Optimisez un site web existant

### Mise en situation

Vous travaillez pour La chouette agence, une grande agence de web design basée à Lyon. L’activité de l’entreprise a bien démarré mais aujourd’hui, elle est en perte de vitesse. Eh oui, la concurrence est rude. La fondatrice de l’entreprise, Sophie, cherche une solution pour faire repartir l’activité. En tapant “Entreprise web design Lyon” sur Internet, elle s’aperçoit que le site de l’agence apparaît seulement en deuxième page des moteurs de recherche. Par chance, un de vos collègues, Martin, lui a dit que vous étiez un spécialiste en référencement.</br></br>

Sophie vous invite dans une réunion pour préciser le périmètre de la mission. Voici le compte-rendu de cette réunion. </br></br>

<table>
    <tr>
        <td>
            De : Sophie
        </td>
    </tr>
    <tr>
        <td>
            A : Camille
        </td>
    </tr>
    <tr>
        <td>
            Objet : Compte-rendu - réunion de lancement “Amélioration du référencement"
        </td>
    </tr>
    <tr>
        <td>
            Bonjour ! </br></br>
            Pour faire suite à notre réunion de tout à l’heure, voici un compte-rendu de ce qui a été
            décidé.</br></br>
            Pour rappel, notre site n’apparaît qu’en deuxième page des moteurs de recherche. Pour cela,
            je souhaiterais que notre référencement soit amélioré.</br></br>
            Voici les points sur lesquels tu devras travailler :</br></br>
            - <b>Analyse de l’état actuel de SEO du site fourni.</b> J’aimerais que tu indiques les parties du site qui ne sont pas optimisées pour le SEO et/ou qui ne sont pas à jour en termes d’accessibilité, et que tu justifies tes choix. Pense à ajouter la bonne pratique à mettre en place pour chaque partie du site qui n’est pas optimisée, en citant tes sources. Tu trouveras ci-joint un modèle pour réaliser ton analyse. Une fois ce modèle complété, j’aimerais que tu sélectionnes 10 recommandations pour améliorer le site. Je te laisse cocher ces 10 recommandations choisies dans la colonne “Action recommandée”. Il faudra bien garder en tête que le but est que notre site soit mieux classé lorsqu’on tape “Entreprise webdesign Lyon” dans les moteurs de recherche. Martin voudrait qu’il y en ait au moins une sur la vitesse et la taille du site et une sur l’accessibilité. Actuellement, certains de nos utilisateurs rencontrent des problèmes d’accessibilité sur notre site, c’est un point sur lequel on veut s’améliorer. Tu devras donc ajouter les éléments nécessaires. La liste de ce que tu devras implémenter se trouve à cette adresse. </br>
            - <b>Amélioration du SEO du site.</b> Il faudra ensuite optimiser notre site en appliquant tes 10 recommandations à son contenu et à son code source. Tu devras pour cela fournir le code source complet de la version améliorée du site. Le site doit passer le W3C pour HTML et CSS.</br>
            - <b>Comparaison des résultats.</b> La vitesse de chargement des pages du site a un impact sur notre classement dans les résultats de recherche. Dans tes différentes recommandations, j’aimerais que tu prennes des mesures pour accélérer la vitesse de chargement, et que tu me démontres que cela fonctionne, grâce à des captures d’écran comparatives entre la version du site actuelle et celle que tu auras optimisée, fourni dans un rapport d’optimisation. Ce rapport devra inclure les comparaisons pour les 10 recommandations.</br></br>
            Tu l’imagines, tous ces éléments devront être codés en HTML et CSS. Fais également attention à ce que le site soit toujours adapté à toutes les tailles d’écran après tes modifications.</br></br>
            Voilà, je crois que j’ai fait le tour ! N’hésite pas si tu as la moindre question.</br></br>
            Tu trouveras en pièce jointe une maquette de notre site en son état actuel. </br></br>
            Sophie Vasseur - Fondatrice de la chouette agence
        </td>
    </tr>
</table>

### Résultat Lighthouse :

- Rapport lighthouse : https://data.kappli.eu/lachouetteagenceo/rapports/lachouetteagenceo_rapport_SEO_min.png
- Rapport lighthouse détaillé : https://data.kappli.eu/lachouetteagenceo/rapports/lachouetteagenceo_rapport_SEO_détaillé.pdf

### Améliorations apportées (10 demandés) :

10 améliorations étaient demandées par Openclassrooms, j'en ai effectué 13. D'autres améliorations restent à faire pour avoir un meilleur score </br>

<table>
    <tr>
        <td>Type</td>
        <td>Problème identifié</td>
        <td>Pratique à adopter</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Manque de métadonnées</td>
        <td>Mise en place d'un titre, de mot clés, d'une description et d'une balise robots</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Nom du fichier de la page2</td>
        <td>Renommer le fichier et le nommer contact.html</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Chargement lent</td>
        <td>Réduire la taille des images quand c'est nécessaire</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Balise sémantique manquante</td>
        <td>Ajouter des balises de type header, nav, section, ...</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Erreur au W3C sur la lang et le css</td>
        <td>Mettre lang sur fr et corriger les erreurs de css</td>
    </tr>
    <tr>
        <td>SEO</td>
        <td>Lien non utile qui perturbe le référencement</td>
        <td>Supprimer les liens</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Erreur lien vers bootstrap</td>
        <td>Corriger lien vers bootstrap</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Texte trop petit</td>
        <td>Agrandir le texte</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Couleur texte/icône (pas assez de contraste)</td>
        <td>Changement de couleur</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Trait en fond perturbant la lecture du texte</td>
        <td>Suppression du fond</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Texte en image (impossible pour les logiciels pour malvoyant de lire le texte)</td>
        <td>Mettre le texte dans des balises adaptées</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Lien page2</td>
        <td>Mettre le nom de la page (contact)</td>
    </tr>
    <tr>
        <td>Accessibilité</td>
        <td>Alt des images mal écrit</td>
        <td>Réécrire les alt des images</td>
    </tr>
</table>

### Voir le site amélioré : 

- Lien GitHub du code amélioré : https://github.com/KappliApp/Kappli_Camille_Crapat_ProjetOpenclassrooms_La-Chouette-Agence_Am-lior-

### Stack utilisée :
- HTML
- CSS

### Autres informations :
- Voir le site d'origine : https://lachouetteagenceo.kappli.eu/
- Voir le site avec les améliorations : https://lachouetteagence.kappli.eu/
- Profil Linkedin : https://www.linkedin.com/in/camille-crapat-399816214/
- Portfolio : https://kappli.eu
- GitHub : https://github.com/KappliApp/