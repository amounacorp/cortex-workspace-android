# Cortex Workspace pour Android

Application mobile de [Cortex Workspace](https://cortexworkspace.app) (Amouna Corp), construite a partir de
l'application [Nextcloud Android](https://github.com/nextcloud/android), version `stable-35.0.2`, sous licence GPL-2.0.

## Modifications apportees (branche `cortex`)

- Identifiant `app.cortexworkspace.android`, nom, couleurs et icones Cortex Workspace (saveur `generic`) :
  `app/build.gradle.kts`, `app/src/generic/res/`, `app/src/generic/google-services.json`.
- Connexion : l'utilisateur saisit son email professionnel ; `https://app.cortexworkspace.app/api/mobile/login`
  trouve l'espace de son entreprise et relaie le protocole de connexion Nextcloud (login flow v2).
- Chaine de compilation : `.github/workflows/cortex-apk.yml` (les chaines d'origine sont retirees de cette branche).

Le code source de cette application reste public, conformement a la licence GPL-2.0.
Nextcloud est une marque de Nextcloud GmbH ; cette application n'est ni affiliee ni approuvee par Nextcloud GmbH.
