# Confidentialité

IA Locale Facile Studio fonctionne sur ton PC. Tes prompts, tes images, tes vidéos et tes conversations restent dans le
dossier de l'application : rien n'est envoyé à l'éditeur, et l'application ne contient ni pistage ni publicité.

## Connexions à Internet

L'application ne se connecte que dans ces cas, à ta demande :

| Quand | Vers | Ce qui est transmis |
|---|---|---|
| Installation du moteur et des modèles | github.com, pypi.org, download.pytorch.org, huggingface.co | La demande de téléchargement (ton adresse IP est visible de ces sites) |
| Modèle qui exige un compte | huggingface.co | Ton jeton d'accès Hugging Face, si tu l'as enregistré |
| Recherche de modèles (édition Premium) | huggingface.co, civitai.com | Les mots recherchés, et ta clé Civitai si tu l'as enregistrée |
| Achat de l'édition Premium | paypal.com, serveur de licences de l'éditeur | Le code de ton PC (un identifiant haché, sans donnée personnelle), pour créer ta clé |
| Vérification des mises à jour | github.com | La demande de la dernière version |

Une fois reçue, la clé Premium est vérifiée sur ton PC, sans connexion.

## Ce qui est gardé sur ton PC

- `data/` : réglages, code PIN, licence, historique des conversations, jetons d'accès que tu as saisis.
- `outputs/` : tes créations. `models/` : les modèles téléchargés.

Supprimer le dossier de l'application supprime tout.

## Téléphone (édition Premium)

Le téléphone se connecte directement au PC sur ton réseau local, avec un code PIN. Rien ne passe par un serveur extérieur.

## Achat de l'édition Premium

Les données liées à l'achat (e-mail, code du PC, paiement) sont décrites dans les conditions générales de vente.
