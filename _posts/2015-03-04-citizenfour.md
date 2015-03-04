---
layout: post
title: Citizenfour
---

Aujourd'hui est sorti le documentaire sur [les révélations d'Edward Snowden](http://fr.wikipedia.org/wiki/Révélations_d%27Edward_Snowden) sur la surveillance mondiale des réseaux de télécommunications. <span class="meta">Je ne sais pas pourquoi la page Wikipédia anglaise s'arrête à août 2014 tandis que la page française poursuit sa description.</span> Le volume de documents révélés s'élève à 1,7 million.

> Près de 55 % des électeurs américains considèrent que le jeune homme de 30 ans est un « lanceur d'alerte », contre 34 % qui jugent qu'il a trahi son pays.

Parlons de l'histoire du documentaire :

{% img /public/img/greenwald.png %}

Comme indiqué par [djb](http://cr.yp.to/djb.html) au [30C3](http://en.wikipedia.org/wiki/Chaos_Communication_Congress) <span class="meta">(je vous suggère de regarder la vidéo en entier, d'ailleurs, on en apprend beaucoup sur 2013 en cryptologie)</span> :

> This is an example to how unusable today's high-security cryptographic solutions are.

{% youtube HJB1mYEZPPA?t=9m30s %}

## Cryptographie

Justement, plutôt que de parler du documentaire, mentionnons les [outils cryptographiques qui ont rendu possible la communication entre Snowden et Poitras](http://www.wired.com/2014/10/laura-poitras-crypto-tools-made-snowden-film-possible/), la réalisatrice :

### [Tor Project](http://fr.wikipedia.org/wiki/Tor_(réseau))

J'ai essayé de l'installer. Heureusement, ils ont un téléchargement en un clic. Ça marche !

Le lancement s'accompagne de conseils utiles :

- Use the Tor Browser
- Don't torrent over Tor
- Don't enable or install browser plugins
- Use HTTPS versions of websites
- Don't open documents downloaded through Tor while online
- Use bridges and/or find company

> If you must work with DOC and/or PDF files, we strongly recommend either using a disconnected computer, downloading the free VirtualBox and using it with a virtual machine image with networking disabled, or using Tails.

### Tails

Un [système d'exploitation basé sur Tor](https://tails.boum.org).

## [GPG](http://fr.wikipedia.org/wiki/GNU_Privacy_Guard)

Il s'agit d'un système permettant aux utilisateurs de transmettre des messages signés ou chiffrés. [4 millions d'utilisation en 20 ans.](http://www.thoughtcrime.org/blog/gpg-and-me/) Mouais.

<blockquote class="twitter-tweet" lang="fr"><p>I used to dream of a world where everyone would install GPG. Now I dream of a world where I can uninstall it: <a href="http://t.co/eRZ0hdlmgx">http://t.co/eRZ0hdlmgx</a></p>&mdash; Moxie Marlinspike (@moxie) <a href="https://twitter.com/moxie/status/570358236806668288">24 Février 2015</a></blockquote> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

### [Off-The-Record Messaging (OTR)](http://fr.wikipedia.org/wiki/Off-the-Record_Messaging)

Un protocole cryptographie pour sécuriser les communications via messagerie instantanée.

### [SecureDrop](https://en.wikipedia.org/wiki/SecureDrop)

Pour l'upload de fichiers sécurisé. Développé par feu [Aaron Swartz](https://fr.wikipedia.org/wiki/Aaron_Swartz) (!) et Kevin Poulsen.

### [Truecrypt](https://fr.wikipedia.org/wiki/TrueCrypt)

Pour le chiffrement du disque dur.

À vous de jouer !
