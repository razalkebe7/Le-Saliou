LE SALIOU — BOUTIQUE E-COMMERCE PREMIUM (BASE ÉVOLUTIVE)

OUVRIR LE SITE
1. Décompresse Le_Saliou_Premium.zip.
2. Ouvre index.html avec Chrome, Edge ou Firefox.
3. Une connexion Internet est nécessaire pour charger les polices et les photos distantes.

PERSONNALISER LES COMMANDES WHATSAPP
1. Ouvre config.js avec un éditeur de texte.
2. Remplace REMPlACER_PAR_TON_NUMERO par ton numéro international sans + ni espaces.
   Exemple fictif Sénégal : 221771234567.
3. Enregistre puis recharge le site.
4. Teste avec une petite commande de test.

MODIFIER LES PRODUITS
Les exemples se trouvent au début de app.js dans le tableau "products".
Chaque produit possède : id, name, category, price, tag, image et description.
Catégories disponibles : Maison, Style, Quotidien.
Les prix sont des exemples en FCFA. Remplace toutes les fiches et photos par ton catalogue réel.
Les images sont chargées depuis Unsplash ; remplace les URL par tes photos produit pour une boutique professionnelle cohérente.

CE QUI FONCTIONNE DANS CETTE VERSION
- Design responsive ordinateur/mobile.
- Catalogue exemple, catégories, recherche et tri par prix.
- Panier avec quantités et sous-total, conservé dans le navigateur.
- Formulaire de commande et préparation d'un message WhatsApp.
- Pages Livraison, FAQ, Conditions de vente et Confidentialité.
- Formulaire newsletter de démonstration.

CE QUI N'EST PAS ENCORE UN VRAI SERVICE DE PRODUCTION
- Pas de serveur ni de base de données.
- Pas de compte client ni d'espace administrateur.
- Pas de gestion centralisée des stocks/commandes.
- Pas de paiement en ligne intégré : Wave/Orange Money ne sont pas connectés.
- Le formulaire newsletter n'enregistre pas d'abonnés.
- Les pages légales doivent être adaptées et validées.
- Les produits, les prix et les délais de livraison sont des exemples.

POUR PASSER À UNE BOUTIQUE COMPLÈTE EN PRODUCTION
Il faudra connecter un backend sécurisé et une base de données, un tableau de bord administrateur, l'authentification, la gestion des stocks, des commandes et clients, ainsi qu'un prestataire de paiement compatible avec le Sénégal. Les identifiants et clés secrètes ne doivent jamais être placés dans le JavaScript public.
