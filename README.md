# CY-2023-RATTRAPAGE

## Application Front Angular
Il vous faudra générer le Front d'une application avec Angular. Celle-ci devra se connecter à un projet Firebase pour gérer les données dynamiques. L'application que vous allez créer doit permettre de :
- lister les étudiants présents dans la base de données. Un éudiant comprendra les données minimales suivantes : nom, prénoms (tableau), promotion, spécialités (tableau), photo ;
- éditer un étudiant (l'ensemble des données) ;
- supprimer un étudiant.
La liste des étudiants sera accessible après authentification ; utilisez Firebase Authentication pour ce faire.
L'application Angular que vous développerez devra comprendre l'ensemble des outils de sécurisation incluant : guard, interceptor et lazy loading sur les routes des étudiants.

Le projet doit être rendu IMPERATIVEMENT sur le dépôt dédié sur Github Classroom.

## Application Back serverless AWS CDK
Dans le cadre de ce rattrapage il vous sera demandé de créer une infrastructure Cloud fonctionnelle via le CDK AWS. Les fichiers seront IMPERATIVEMENT téléversés sur le dépôt Github Classroom. 

Le projet que vous ferez devra :
- créer un bucket S3 ;
- créer une lambda permettant d'afficher publiquement la liste des documents disponibles dans le bucket. L'accès public devra se faire via une URL Function ;
- créer une lambda générant une vignette de toute image téléversée dans le bucket.

Les lambdas recevront en paramètre de configuration une variable d'environnement permettant de connaître le bucket à interroger.
