EDEN MARKET V3 — Supabase

1) Ouvre config.js.
2) Remplace COLLE_ICI_TA_CLE_PUBLISHABLE_SUPABASE par la clé Publishable/anon de ton projet Supabase.
3) Ne mets JAMAIS une clé service_role/secret dans ce fichier.
4) Ouvre index.html pour le site client.
5) Ouvre admin.html pour le Studio Créateur.
6) Pour Google: Supabase > Authentication > Providers > Google, puis ajoute le Client ID/Secret Google. L'URL de callback Supabase est affichée par Supabase dans cette page.
7) Pour un hébergement statique, envoie tout le dossier sur Cloudflare Pages. Le fichier config.js doit rester à côté de index.html et admin.html.

Compte admin déjà préparé côté base: ton utilisateur doit avoir profiles.role = admin.
Le panier/favoris anonymes sont locaux; les commandes nécessitent une connexion.
Paiement: paiement à la livraison.
