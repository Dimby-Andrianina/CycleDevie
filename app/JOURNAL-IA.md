# Journal IA - TP 3 — Andrianantenaina Dimbinekena

- Diagnostic soumis : NullPointerException sur `findViewById(R.id.btnPartage)` à la ligne 29.
- Mon verdict en 3 lignes :
  L'IA désigne correctement la ligne 29 de MainActivity et identifie bien que `findViewById` retourne `null`.
  Sa correction est cependant fausse : elle propose d'ajouter `btnPartage` dans le XML, mais le fichier `activity_main.xml` contient déjà `@+id/btnPartager` (avec un "r").
  La vraie correction est donc de remplacer `R.id.btnPartage` par `R.id.btnPartager` dans le code Kotlin de la ligne 29.