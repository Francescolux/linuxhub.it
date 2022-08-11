---
title: 'Canonical invia aggiornamenti di sicurezza via mail agli sviluppatori snap'
date: 2018-05-04
layout: post
author: Mirko B.
author_github: mirkobrombin
coauthor: linuxhub
coauthor_github: linuxhubit
tags:
  - ubuntu
---
Canonical invia aggiornamenti via e-mail "<strong>USN</strong>" (Ubuntu Security Notifications) che contengono i dettagli sulle ultime correzioni di sicurezza per i pacchetti in staging a tutti gli sviluppatori di applicazioni snap.I pacchetti snap hanno come pilastro della loro progettazione la sicurezza, poiché vengono eseguiti come containers e lavorano indifferentemente dal resto del sistema host. Si aggiornano automaticamente, sono semplici da installare senza il trambusto di innumerevoli dipendenze. Tuttavia, i nuovi avvisi di sicurezza di Canonical per gli sviluppatori li rendono ancora più sicuri.<a href="https://linuxhub.it/wordpress/wp-content/uploads/2018/05/Snap-USN-Notification4.png"><img class="aligncenter size-full wp-image-4660 size-full wp-image-390" src="https://linuxhub.it/wordpress/wp-content/uploads/2018/05/Snap-USN-Notification4.png" alt="" width="883" height="698" /></a>Se sei uno sviluppatore snap, puoi decidere di attivare queste notifiche di sicurezza dallo snap/manifest.yaml nel tuo pacchetto Snap, che può essere generato automaticamente dal Launchpad.É inoltre possibile impostare manualmente la variabile di ambiente <strong>SNAPCRAFT_BUILD_INFO</strong> <strong>= 1</strong> nel manifest.yaml del pacchetto snap prima di impacchettare l'applicazione con Snapcraft. Per impostazione predefinita, gli avvisi verranno inviati al tuo indirizzo email registrato.<strong>USN</strong> | <a href="https://usn.ubuntu.com/">https://usn.ubuntu.com/</a><strong>Annuncio ufficiale</strong> | <a href="https://insights.ubuntu.com/2018/05/02/introducing-developer-notifications-for-snap-security-updates">https://insights.ubuntu.com/2018/05/02/introducing-developer-notifications-for-snap-security-updates</a>