---
title: users#show
category: Requêtes
url_path: "/users/:id.json"
type: GET
layout: null
---

### Paramètres

| Paramètre | **Type** | Mode de transmission | Description                |
| --------- | -------- | -------------------- | -------------------------- |
| Id        | string   | query                | Identifiant de la ressource |

### Réponse

Retourne une représentation de la ressource :

```
user
```

Exemple :

```json
{
  "id": "5a54e226d95bd83fcd736f1e",
  "first_name": "John",
  // ... voir type de ressource "User"
}
```
