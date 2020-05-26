## Lundi 25 Mai 2020

### Objectifs

Les objectifs de la journée sont lire l'énoncé, rédiger le backlog ainsi que les scénarios et faire la planification.

### Déroulement

__08h00:__ Je commence ma journée en lisant l'énoncé (ce qui correspond à l'étape _S'informer_ de la méthode en 6 étapes).
J'ai compris presque la totalité de l'énoncé sauf pour le critère A19 15) qui dit: 
> Après l’inscription, l’utilisateur peut voir l’événement dans la zone.

Car je ne vois pas ce qu'est la zone.

Je me demande si les invités aux événements privés reçoivent un mail les prévenant qu'ils sont invités à l'événement.

Et aussi je me demande si les utilisateurs invités à un événement privé s'il reçoit un mail.

Donc j'ai décidé d'attendre ma formatrice qui passe à 11h30.

__08h20:__ Je finis de lire l'énoncé et je commence à rédiger le backlog.
Pour définir un ordre de priorité pour les _story_ du backlog, j'ai utilisé la méthode __MoSCoW__.

* ❗❗ L'équivalent de __Must:__ sera __Indispensable__
* ❗ L'équivalent de __Should:__ sera __Critique__

J'ai choisis de retirer le __Could__ et le __Won't__ car je ne dois pas déborder du cahier des charges lors de cet examen mais si j'avais pu déborder du cahier des charges j'aurai pu mettre en __Should__ le fait d'envoyer un mail aux personnes qui sont invités à un événement privé.

Chaque _user story_ est rédigé sous le format suivant:

> | Nom             | S.<n° de la story> _Nom de de la story_    |
> | --------------- | -------------------------------------------|
> | __Description__ | _Description de la story_                  |
> | __Test(s)__     | _Numéro des tests qui valide la story_     |
> | __Priorité__    | _Priorité de la story_                     |

__10h45:__ Je finis de rédiger le backlog et je commence à rédiger mon planning.
Pour le planning prévisionnel et le planning effectif, j'ai utilisé la couleur <span style="color:#3993fa">#3993fa</span> afin de marquer les jalons.

__11h30:__ J'ai un entretien avec Mme Mota afin de voir si ma matinée s'est bien déroulée et j'ai pu lui demander pour le point A19.
Lors de l'entretien, on va vérifier si la syntaxe de mon backlog est correcte, répondre aux 2 questions que je me suis posé durant la matinée.

❔ Je ne comprend pas ce qu'est la "zone" cité dans le point A19 15, pourriez-vous m'aider comprendre ?
> Réponse: La zone est dans la page sur laquelle on peut gérer ses événements.

❔ Est-ce que je dois envoyer un mail aux utilsateurs afin de les prévenir qu'ils sont invités à un événement privé ?
> Réponse: Il ne faut  pas envoyer de mail à ce moment-là, c'est seulement lors de l'inscription d'un événement.

Après l'entretien, je vais devoir rajouter des tâches dans mon backlog, car je ne recouvre pas toutes les demandes du cahier des charges.

__12h35:__ Fin de l'entretien avec Mme Mota, on a fixé un nouvel entretien aujourd'hui à 16h.

__12h50:__ Je prends ma pause de midi.

__13h35:__ Je reprends mon travail sur le backlog.

__14h50:__ Je finis de rédiger le planning prévisionnel et je l'ai implémenté avec le backlog dans la documentation. Je commence à corriger les erreurs de grammaire de mon journal de bord et de la documentation.

__15h15:__ Je commence à rédiger les scénarios de tests sous le format suivant :

> |         Nom         | <n° du test>.<n° du cas de test> _Nom du test_ (<span style="color:#27c229">données valides</span> / <span style="color: #e00d13">données invalides</span>) |
> | :-----------------: | ------------------------------------------------------------ |
> |   __User Story__    | S.<n° de la story>                                           |
> |    __Situation__    | _Description de tout le test_                                |
> | __Résultat obtenu__ | _Résultat du test_                                           |
> |     __Statut__      | ❌ KO / ✅ OK                                               |

__16h00:__ Entretien avec Mme Mota.

__17h35:__ Je finis mon entretien avec Mme Mota. Normalement ma journée devrait se terminer à __17h00__, mais aujourd'hui je continue à travailler.

__18h10:__ Je finis ma journée.

### Bilan

Ma première journée de TPI s'est terminée, j'avais prévu de faire trop de tâches aujourd'hui alors j'ai commencé à prendre su retard sur mon planning donc demain je vais finir de rédiger les scénarios. Durant la journée, j'ai rencontré des problèmes de compréhension avec l'énoncé, mais j'ai pu répondre à mes interrogations grâce aux deux entretiens faits avec Mme Mota.

---

## Mardi 26 Mai 2020

### Objectifs

Les objectifs de la journée sont finir de rédiger les scénarios, créer le dépôt Git, l'implémentation de la base de données et la configuration de Composer.

### Déroulement

__08h00:__ Je commence ma journée en continuant la rédaction des scénarios.

__8h30:__ Je vois que la rédaction me prend beaucoup de temps donc j'ai décidé d'arrêter pour les scénarios et de mettre en place la base données car étant un jalon je me dois de la faire en priorités.

__8h40:__ Je commence la création de la base de données.

__9h00:__ J'ai finis de créer la base de données et de la mettre dans le serveur local. Je continue ma matinée en mettant la base de données dans la documentation.

__9h45:__ Je finis de mettre les informations en lien avec la base de données dans la documentation. Ensuite je créer le dépôt Git.

__9h55:__ Je finis initialisation du dépôt Git. Et je commence à mettre en place Composer et ses dépendances.

__10h00:__ Je finis d'installer Composer et ses dépendances et je reprends mon travail sur les scénarios.

__11h00:__ J'ai un entretien avec Mme Mota.

Durant cet entretien j'ai demandé à Mme Mota :

❔ Faut-il ajouter directement tous les utilisateurs d'un événements privé ou on peut en les ajouter en ajouter une partie et ajouter la suite après avoir créer l'événement ?

> Réponse: Il faut ajouter tous les invités lors de la création de l'événement.

J'ai aussi pris le choix avec Mme Mota de ne pas rédiger tous les scénarios de tests d'un coup mais les rédiger au début de la journée et à la fin de la journée.

__12h10:__ Fin de l'entretien avec Mme Mota et j'ai complété mon journal de bord.

__12h30:__ Correction des scénarios rédigé.

__12h40:__ Je prends ma pause du midi.

__13h25:__ Je finis ma pause midi créer un deuxième dépôt Git afin d'en avoir un spécialement pour la documentation et un autre spécialement pour le code source.

__13h40:__ Je finis la séparation et je commence à développer l'inscription.

__16h10:__ Je finis de développer et de tester l'inscription.

### Bilan



---