## Lundi 25 Mai 2020

### Objectifs

Les objectifs de la journée sont lire l'énoncé, rédiger le backlog ainsi que les scénarios et faire la planification.

### Déroulement

**08h00:** Je commence ma journée en lisant l'énoncé (ce qui correspond à l'étape _S'informer_ de la méthode en 6 étapes).
J'ai compris presque la totalité de l'énoncé sauf pour le critère A19 15) qui dit:

> Après l’inscription, l’utilisateur peut voir l’événement dans la zone.

Car je ne vois pas ce qu'est la zone.

Je me demande si les invités aux événements privés reçoivent un mail les prévenant qu'ils sont invités à l'événement.

Et aussi je me demande si les utilisateurs invités à un événement privé s'il reçoit un mail.

Donc j'ai décidé d'attendre ma formatrice qui passe à 11h30.

**08h20:** Je finis de lire l'énoncé et je commence à rédiger le backlog.
Pour définir un ordre de priorité pour les _story_ du backlog, j'ai utilisé la méthode **MoSCoW**.

- ❗❗ L'équivalent de **Must:** sera **Indispensable**
- ❗ L'équivalent de **Should:** sera **Critique**

J'ai choisis de retirer le **Could** et le **Won't** car je ne dois pas déborder du cahier des charges lors de cet examen mais si j'avais pu déborder du cahier des charges j'aurai pu mettre en **Should** le fait d'envoyer un mail aux personnes qui sont invités à un événement privé.

Chaque _user story_ est rédigé sous le format suivant:

> | Nom             | S.<n° de la story> _Nom de de la story_ |
> | --------------- | --------------------------------------- |
> | **Description** | _Description de la story_               |
> | **Test(s)**     | _Numéro des tests qui valide la story_  |
> | **Priorité**    | _Priorité de la story_                  |

**10h45:** Je finis de rédiger le backlog et je commence à rédiger mon planning.
Pour le planning prévisionnel et le planning effectif, j'ai utilisé la couleur <span style="color:#3993fa">#3993fa</span> afin de marquer les jalons.

**11h30:** J'ai un entretien avec Mme Mota afin de voir mon avancement. afin de voir si ma matinée s'est bien déroulée et j'ai pu lui demander pour le point A19.
Lors de l'entretien, on va vérifier si la syntaxe de mon backlog est correcte, répondre aux 2 questions que je me suis posé durant la matinée.

❔ Je ne comprend pas ce qu'est la "zone" cité dans le point A19 15, pourriez-vous m'aider comprendre ?

> Réponse: La zone est dans la page sur laquelle on peut gérer ses événements.

❔ Est-ce que je dois envoyer un mail aux utilisateurs afin de les prévenir qu'ils sont invités à un événement privé ?

> Réponse: Il ne faut pas envoyer de mail à ce moment-là, c'est seulement lors de l'inscription d'un événement.

Après l'entretien, je vais devoir rajouter des tâches dans mon backlog, car je ne recouvre pas toutes les demandes du cahier des charges.

**12h35:** Fin de l'entretien avec Mme Mota, on a fixé un nouvel entretien aujourd'hui à 16h.

**12h50:** Je prends ma pause de midi.

**13h35:** Je reprends mon travail sur le backlog.

**14h50:** Je finis de rédiger le planning prévisionnel et je l'ai implémenté avec le backlog dans la documentation. Je commence à corriger les erreurs de grammaire de mon journal de bord et de la documentation.

**15h15:** Je commence à rédiger les scénarios de tests sous le format suivant :

> |         Nom         | <n° du test>.<n° du cas de test> _Nom du test_ (<span style="color:#27c229">données valides</span> / <span style="color: #e00d13">données invalides</span>) |
> | :-----------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
> |   **User Story**    | S.<n° de la story>                                                                                                                                          |
> |    **Situation**    | _Description de tout le test_                                                                                                                               |
> | **Résultat obtenu** | _Résultat du test_                                                                                                                                          |
> |     **Statut**      | ❌ KO / ✔ OK                                                                                                                                                |

**16h00:** Entretien avec Mme Mota.

**17h35:** Je finis mon entretien avec Mme Mota. Normalement ma journée devrait se terminer à **17h00**, mais aujourd'hui je continue à travailler.

**18h10:** Je finis ma journée.

### Bilan

Ma première journée de TPI s'est terminée, j'avais prévu de faire trop de tâches aujourd'hui alors j'ai commencé à prendre du retard sur mon planning donc demain je vais finir de rédiger les scénarios. Durant la journée, j'ai rencontré des problèmes de compréhension avec l'énoncé, mais j'ai pu répondre à mes interrogations grâce aux deux entretiens faits avec Mme Mota.

---

## Mardi 26 Mai 2020

### Objectifs

Les objectifs de la journée sont finir de rédiger les scénarios, créer le dépôt Git, l'implémentation de la base de données, la configuration de Composer, de développer l'inscription, la connexion et la gestion des accès au site .

### Déroulement

**08h00:** Je commence ma journée en continuant la rédaction des scénarios.

**8h30:** Je vois que la rédaction me prend beaucoup de temps donc j'ai décidé d'arrêter pour les scénarios et de mettre en place la base données car étant un jalon je me dois de la faire en priorités.

**8h40:** Je commence la création de la base de données.

**9h00:** J'ai finis de créer la base de données et de la mettre dans le serveur local. Je continue ma matinée en mettant la base de données dans la documentation.

**9h45:** Je finis de mettre les informations en lien avec la base de données dans la documentation. Ensuite je créer le dépôt Git.

**9h55:** Je finis initialisation du dépôt Git. Et je commence à mettre en place Composer et ses dépendances.

**10h00:** Je finis d'installer Composer et ses dépendances et je reprends mon travail sur les scénarios.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement..

Durant cet entretien j'ai demandé à Mme Mota :

❔ Faut-il ajouter directement tous les utilisateurs d'un événements privé ou on peut en les ajouter en ajouter une partie et ajouter la suite après avoir créer l'événement ?

> Réponse: Il faut ajouter tous les invités lors de la création de l'événement.

J'ai aussi pris le choix avec Mme Mota de ne pas rédiger tous les scénarios de tests d'un coup mais les rédiger au début de la journée et à la fin de la journée.

**12h10:** Fin de l'entretien avec Mme Mota et j'ai complété mon journal de bord.

**12h30:** Correction des scénarios rédigé.

**12h40:** Je prends ma pause du midi.

**13h25:** Je finis ma pause midi et je créer un deuxième dépôt Git afin d'en avoir un spécialement pour la documentation et un autre spécialement pour le code source.

**13h40:** Je finis de mettre en place les deux dépôts Git et je commence à développer l'inscription.

**16h10:** Je finis de développer et de tester l'inscription et je commence à développer la connexion au site.

**17h00:** Fin de journée.

### Bilan

Aujourd'hui j'ai pu faire une grande partie de ce que je souhaitais, malheureusement je n'ai pas eu le temps faire la gestion des accès. J'ai fais le choix de ne pas faire tous les scénarios de tests d'un coup mais quelque scénario le matin et en fin de journée.

---

## Mercredi 27 Mai 2020

### Objectifs

Les objectifs de la journée sont faire la gestion des accès, la création d'événement la création de la liste d'invités pour un événement privé, l'affichage des événements et la page qui contient les informations d'un événement.

### Déroulement

**08h00:** Je commence ma journée en rédigeant les scénarios pour la gestion des accès, pour l'affichage des événements et pour la page qui contient les informations d'un événement.

**08h30:** Je finis de rédiger les scénarios prévus et je commence développer la gestion des accès

**9h00:** Je finis de développer la gestion des accès et je commence à développer la création d'événement.

**11h30:** J'ai un entretien avec Mme Mota afin de voir mon avancement.

Mme Mota est revenue sur la question :
❔ Faut-il ajouter directement tous les utilisateurs d'un événements privé ou on peut en les ajouter en ajouter une partie et ajouter la suite après avoir créer l'événement ?

En me disant qu'il faudrait gérer le nombre maximal de personnes invités à l'événement privé de la même manière que les événements publiques c'est-à-dire qu'on est pas obligé d'inviter toutes les personnes dès la création de l'événement.

**11h55:** Fin de l'entretien avec Mme Mota.

**12h10:** Je prends ma pause midi.

**13h00:** Je fini ma pause midi. Et je reprends la création d'un événement.

**14h50:** Je mets en pause le développement de la création d'événement pour ajouter une colonne pour le _salt_ dans la modifier la base de données afin d'avoir une meilleure sécurité dans le site.

**15h00:** Je finis d'ajouter la colonne dans la base de données. Je vais l'implémenter dans l'inscription et pour la connexion.

**15h20:** Je finis d'implémenter le _salt_ pour l'inscription et la connexion et je reprend la création d'événement.

**15h50:** Je finis de développer et de tester la création d'événement publique.

**16h00:** Je commence à développer la création de la liste des invités pour un événements privés.

**18h00:** Je finis ma journée.

### Bilan

Aujourd'hui j'ai pu faire que la moitié de ce que je souhaitais car le style du site m'a pris beaucoup plus de temps que ce que j'avais prévu. Je n'ai pas pu finir la création de la liste des invités à un événement privé car lorsque ma modal pour ajouter des invités apparaît, les données se sont déjà envoyées. Je n'ai pas pu faire l'affichage des événements non plus donc je vais finir ces 2 tâches pour demain.

---

## Jeudi 28 Mai 2020

### Objectifs

Les objectifs de la journée sont finir la création de la liste pour des invités à un événement privé, faire l'affichage des événements, faire la page qui contient les informations de l'événement et l'inscription à un événement ouvert.

### Déroulement

**08h00:** Je commence ma journée en travaillant sur la création de la liste des invités pour un événements privé.

**9h00:** J'ai un entretien avec mes experts afin de voir si mon TPI se déroulait sans encombre.

**09h10:** Fin de entretien avec mes experts.

**10h20:** Je finis la création de la liste d'invités et je commence l'affichage des événements.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement.

**11h20:** Fin de l'entretien avec Mme Mota et je reprends l'affichage des événements.

**12h35:** Je finis l'affichage des événements.

**12h40:** Je prends ma pause midi.

**14h05:** Fin de ma pause midi et je reprend mon travail sur inscription à un événement ouvert.

**15h35:** Je finis la logique de l'inscription à un événement ouvert.

**17h25:** Je finis ma journée.

### Bilan

Aujourd'hui j'ai presque fait tout ce que j'avais prévu.

Avec Tanguy Cavagna (un camarde de classe) on a réussis à résoudre le problème avec la liste d'invités en utilisant un _fetch()_

```javascript
return fetch("url", {
  method: "",
  headers: {
    Accept: "",
    "Content-Type": "",
  },
}).then((response) => response.json());
```

Au lieu d'un appel _ajax_

```javascript
$.ajax({
  type: "method",
  url: "url",
  data: "data",
  dataType: "dataType",
  success: function (response) {},
});
```

Car avec un appel ajax on ne peut pas mettre le _success:_ en asynchrone alors qu'avec un _fetch_ on peut le mettre en asynchrone.

Mais je n'ai pas pu finir à 100% l'inscription à un événement publique, j'ai réussi à faire toutes la logique mais j'ai pas réussi à faire un style qui fonctionne une fois qu'on c'est inscrit à plusieurs événements, donc je vais finir cette tâche demain.

---

## Vendredi 29 Mai 2020

### Objectifs

Les objectifs de la journée sont de finir inscription à un événement publique et commencer à faire la page pour la gestion des événements.

### Déroulement

**08h00:** Je commence ma journée en reprenant le travail sur inscription à un événement publique.

**8h25:** Je finis l'inscription à un événement privé. Et je commence l'affichage de la page de gestion des événements.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement.
Durant cet entretien Mme Mota m'a demandé de faire un logo afin d'avoir une identité visuel pour mon site.

**11h40:** Fin de l'entretien avec Mme Mota et je reprends mon travail sur la page gestion des événements.

**12h25:** Je prends ma pause midi.

**13h20:** Fin de ma pause midi et je me remets à travailler sur la page de gestion des événements.

**15h00:** Je pars pour mon rendez-vous chez le médecin.

**16h20:** Retour de chez le médecin. Et me remets à travailler sur la page de gestion des événements.

**18h30:** Je finis la page de gestion des événements ce qui finis ma journée, j'ai travaillé plus tard afin rattraper le fait que j'ai eu un rendez-vous chez le médecin.

### Bilan

Aujourd'hui j'ai pu faire tout ce que j'avais prévus, ce qui est une première depuis le début de mon TPI.

---

## Mardi 02 Juin 2020

### Objectifs

Les objectifs de la journée sont faire une page entière avec les informations de l'événements (actuellement il n'y a qu'une carte avec les informations), et faire la validation à un événement.

### Déroulement

**08h00:** Je commence ma journée en travaillant sur la page qui contient les information de l'événement.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement et de me faire un retour sur la documentation intermédiaire rendu vendredi.

Lors de cette entretien on est revenu sur le rendu intermédiaire que j'ai rendu vendredi 29 mai.
Dans les points que je dois revoir dans ma documentation sont:

- La catégorie _Structure du code_(page 5 de l'énoncé).
- Ajout un Rapport fichier rapport de bug pour documenter mes tests (fails)
- Faire en sorte les émoticônes du suivis journalier de tests soit plus visible
- Lister tous les acronymes + leurs signification cités dans le glossaire
- Mettre plus en évidences que j'utilise les outils la méthodologie agile (backlog, Gherkins, rédaction des scénarios de test avant d'implémenter dans l'app)
- Mieux documenter les difficultés
- Ajouter des légendes au tableau et aux images

**12h40:** Fin de l'entretien avec Mme Mota et je reprends mon travail sur l'affichage des informations d'un événement.

**14h10:** Je prends ma pause midi.

**14h45:** Fin de ma pause midi et je me remets à travailler sur la page d'information d'un événement.

**15h20:** Je finis la page d'informations d'un événement. Et je commence à rédiger le scénario de la validation de participation à un événement.

**15h40:** Je finis de rédiger les scénarios et je commence à implémenter la fonctionnalité.

**17h30:** J'ai finis d'implémenter les mails lors de l'inscription à un événement et de le tester. Et je finis ma journée.

### Bilan

Aujourd'hui j'ai pu faire toutes les tâches planifié, j'ai eu du mal avec l'envoie de mail car je n'ai pas beaucoup utilisé mail lors de ma formation mais grâce à la documentation de PHPMailer j'ai pu y arriver. J'ai eu un problème avec l'envoie de mail car une fois que le mail c'était envoyé le message de validation du call ajax n'apparaissais plus et il n'y avait l'actualisation de la page non plus.
Mais en recherchant sur stackoverflow j'ai pu trouver ou était mon problème.

```php
  try {
    //Enable SMTP debugging.
    $mail->SMTPDebug = 3;
```

De base la variable STMPDebug est initialisé à `3`, ce qui veut dire qu'un message de validation est envoyé côté client et côté serveur et ceci interférai avec:

```php
  echo json_encode([
    'ReturnCode' => 0,
    'Success' => $successMessage
  ]);
  exit();
```

Dans ma console JavaScript il y avait ceci qui était affiché avec mon message de validation à la fin:

<img src="./assets/phpMailerError.PNG" height="600">

Mais du coup après être allé sur stackoverflow:

```php
  try {
    //Enable SMTP debugging.
    $mail->SMTPDebug = 0;
```

J'ai pu comprendre qu'en initialisant `STMPDebug` à 0 il n'y aurait plus de problème avec mon call ajax.

Aussi aujourd'hui lors de entretien avec Mme Mota elle m'a fait un retour sur la documentation intermédiaire et je me suis rendu compte que j'avais mal compris la partie _Structure du code_ dans l'énoncé (page 5), Mme Mota a passé environ 30 minutes à m'expliquer ce qui était attendu.

[Cliquez ici pour voir la documentation de PHPMailer](https://github.com/PHPMailer/PHPMailer/blob/master/README.md)

---

## Mercredi 03 Juin 2020

### Objectifs

Les objectifs de la journée sont d'implémenter le rappel de la participation à un événement, la suppression d'un événement, l'affichage du profile et commencer la modification d'un événement.

### Déroulement

**08h00:** Je commence ma journée en rédigeant les scénarios du rappel à un événement et la suppression d'un événement.

**08h35:** Je finis de rédiger les scénarios du rappel à un événement, de la suppression d'un événement et de l'affichage de la profile et je commence à implémenter le mail de rappel de la participation à un événement.

**10h35:** Je finis d'implémenter et de tester l'envois du mail qui rappel qu'un événement à lieu le lendemain. Et au lieu de faire la suppression d'un événement.

**11h05:** Je finis d'écrire les scénarios et je commence à implémenter la page profile.

**12h15:** Je finis l'affichage de la page profile. Et je commence à implémenter la suppression de l'événement.

**13h25:** Je prends ma pause midi.

**14h05:** Je finis ma pause midi et je reprends mon travail pour la suppression des événements.

**14h45:** Je finis d'implémenter et de supprimer la suppression d'événement. Et je commence la rédaction des scénarios pour la modification d'un événement.

**15h15:** Je finis de rédiger les scénarios de tests de la modification d'événement et je me mets à l'implémenter dans le site.

**16h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement.
Lors de cette entretien j'ai pu demander à Mme Mota si je pouvais modifier la structure du site afin que ce soit plus pratiquer pour moi. Elle a accepté car aucune ressource n'est impactée par ma modification.
On a aussi vu que ma structure des scénarios était fausse, j'oubliais de mettre la partie **quand** dans la partie _Situation_.

**17h20:** Fin de l'entretien avec Mme Mota et je finis ma journée en même temps.

### Bilan

Aujourd'hui j'ai pu faire ce qui était prévu sans rencontrer de problème. C'est lors de l'entretien avec Mme Mota qu'on s'est rendu compte que la rédaction de mes scénarios était fausse donc je vais les corriger demain.

Au début mes scénarios devait ressembler à ceci :

![scenario_valide](./assets/scenario_valide.png)

Mais à la fin il ressemblais à ceci :

![secnario_invalide](./assets/scenario_invalide.png)

---

## Jeudi 04 Juin 2020

### Objectifs

Les objectifs de la journée sont de finir la modification d'un événements, corriger la rédaction des scénarios et commencer la suppression du profile.

### Déroulement

**08h00:** Je commence ma journée en travaillant sur la correction des scénarios rédigés.

**09h00:** J'ai un entretien avec mes experts afin de voir mon avancement dans mon TPI.

**9h10:** Fin de l'entretien. et je me remets à travailler sur la correction des scénarios.

**10h10:** Je finis de corriger les scénarios de tests et je reprends la modification d'un événement.

**10h50:** Je demande à Mme Mota:
❔ Pour la modification d'un événement est-ce qu'on peut le passer de privé à publique ou de publique à privé ?

> Réponse: Ce n'est pas dans le cahier de charges.

**12h00:** Je prends ma pause midi.

**13h15:** Je finis ma pause midi et je reprends l'implémentation de la modification d'un événement.

**14h30:** Je finis l'implémentation et les test de la modification d'un événement et je commence la rédaction de la suppression du profil.

**14h55:** Je finis la rédaction des scénarios pour la suppression du profil et je commence à implémenter la suppression du profile.

**17h00:** Je finis ma journée.

### Bilan

Aujourd'hui j'ai pu faire toutes les tâches qui étaient prévus. Je n'ai pas eu de point bloquant mais une interrogation sur la modification des événements car je ne savais pas si on pouvais passer un événement de publique à privé et inversément mais Mme Mota m'a dis que ce n'était pas dans le cahier des charges.

---

## Vendredi 05 Juin 2020

### Objectifs

Les objectifs de la journée sont finir la suppression du profile et la faire la modification du profile.

### Déroulement

**08h00:** Je commence ma journée en travaillant sur la suppression du profile.

**09h35:** Je finis la suppression du profile. Et je commence la rédaction des scénarios pour la modification du profile.

**10h15:** Je finis la rédaction des scénarios pour la modification du profile. Et je commence l'implémentation de la modification du profile.

**11h05:** J'ai un entretien avec Mme Mota afin de voir mon avancement.
Lors de l'entretien j'ai pu demandé à Mme Mota:
❔ Je ne vois pas ce qui est attendu dans le point A18 9 veut dire, pourriez-vous m'aider à comprendre ?

> Ce qui est attendu dans ce point c'est qu'un utilisateur soit pouvoir créer un événement privé.

**12h00:** Fin de l'entretien avec Mme Mota et je me remets à travailler sur la modification du profil.

**13h10:** Je prends ma pause midi.

**14h05:** Je finis ma pause midi et je reprends la modification.

**14h50:** Je finis de d'implémenter et de tester la modification et je reprends la modification des événements car je n'avais pas fait en sorte que l'on puisse changer l'image de l'événement.

**15h50:** Je finis la modification des événements et je rejoute une quatrième zone à la page `Gérer mes événements` afin d'avoir une partie qui contient tous les événements qu'on a crée.

**16h30:** Je finis l'implémentation de la quatrième zone. Et je relis mon énoncé du TPI afin d'être sûr que tous ce qui est demandé est complété.

**16h40:** Je finis de relire mon énoncé et je vois qu'il me manque l'affichage de la liste des invités pour le créateur d'un événement privé alors, je commence à faire l'affichage de la liste des invités pour le créateur d'un événement privé.

**17h10:** Je finis d'implémenter l'affichage de la liste d'invités pour le créateur d'un événement privé. Et je commence à créer un logo pour le site.

**17h30:** Je finis le logo du site et je commence à faire une icône pour le site.

**17h40:** Je finis l'icône pour le site et je commence l'implémentation le logo et l'icône dans le site.

**17h55:** Je finis d'implémenter les le logo et l'icône dans le site et je finis ma journée.

### Bilan

Aujourd'hui j'ai pu finir l'implémentation des fonctionnalités et j'ai même pu faire un logo pour le site. Après la relecture de l'énoncé j'ai pu demander à Mme Mota ce que voulais dire le point A18 9 car l'énoncé dit : `9.un utilisateur authentifié un utilisateur authentifié`.

---

## Lundi 08 Juin 2020

### Objectifs

Les objectifs de la journée sont de faire un test de tous le site afin d'être sûr que toutes les fonctionnalités fonctionnent, de faire la partie structure dans la documentation.

### Déroulement

**08h00:** Je commence ma journée en testant le site.

**08h05:** Je vois qu'on ne peut pas supprimer d'événement privé à cause de la liste d'invités.

**08h20:** Je finis la suppression d'un événement privé et je reprends le test de toutes les fonctionnalités du site.

**09h10:** Je commence à implémenter la page `But du site`.

**09h55:** Fin de l'implémentation de la page `But du site`. Et je commence à rédiger la partie structure dans la documentation.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement.

**11h35:** Fin de l'entretien avec Mme Mota. Et je reprends la structure de la rédaction du projet.

**13h35:** Je finis la rédaction de la de la structure du projet et je prends ma pause midi.

**14h05:** Je finis ma pause du midi et je mts le schéma de la base de données.

**14h35:** Je finis de mettre à jour la base de données dans la docuementation et je commence la description de l'application.

**15h50:** Je finis de mettre la description de l'application et je commence à rédiger l'analyse des fonctionnalités majeures.

**17h10:** Je finis ma journée.

### Bilan

Aujourd'hui j'ai pu faire le test de toute l'application WEB et corriger les quelques bugs que j'ai trouvé, j'ai aussi bien avancé dans ma documentation mais je n'ai pas eu le temps de finir la rédaction des fonctionnalités majeures donc je vais finir cette tâche demain.

---

## Mardi 09 Juin 2020

### Objectifs

Les objectifs de la journée sont finir la documenation technique, la documentation utilisateur et rendre le porjet.

### Déroulement

**08h00:** Je commence ma journée en reprenant le travail sur la rédaction de l'analyse des fonctionnalités majeures.

**8h15:** N'arrivant pas à avancer sur ce sujet je décide de passer à la rédaction de la conclusion.

**11h00:** J'ai un entretien avec Mme Mota afin de voir mon avancement.

### Bilan

---
