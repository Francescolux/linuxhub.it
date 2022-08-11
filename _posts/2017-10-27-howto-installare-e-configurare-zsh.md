---
title: '#howto: Installare e configurare ZSH'
date: 2017-10-27
layout: post
author: Mirko B.
author_github: mirkobrombin
coauthor: linuxhub
coauthor_github: linuxhubit
tags:
  - github  - bash
---
<p><strong>ZSH</strong>&nbsp;(Z Shell) è una <strong>shell</strong> per GNU/Linux, alternativa alla più conosciuta, ed installata di default sulla maggioranza delle distro, <strong>Bash</strong>.</p><p>Questa shell è una delle poche ad essere completamente interattiva, multifunzionale e altamente personalizzabile. Vediamo come installarla e configurarla.</p><h3>Installazione</h3><p>Installate il pacchetto <code>zsh</code>, presente nella maggior parte dei repository ufficiali. Fate riferimento alla&nbsp;<a href="https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH#howto-install-zsh-in-many-platforms">pagina ufficiale</a> per la vostra distribuzione in uso. Una volta installato eseguiamo la procedura guidata, digitiamo quindi nel terminale:</p><pre><code class="language-bash">sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"</code></pre><p>e seguite le istruzioni a schermo. Una volta finito, riavviate il terminale per provare zsh.</p><p>Se doveste vedere la solita Bash, cambiate shell manualmente eseguendo</p><pre><code class="language-bash">chsh -s /bin/zsh. </code></pre><p>Se anche questo non avesse funzionato, eseguite automaticamente ZSH all'avvio di Bash. Per farlo, aprite il file <em><strong>.bashrc</strong></em> digitando</p><pre><code class="language-bash">xdg-open ~/.bashrc</code></pre><p>e sotto la seguente riga&nbsp;</p><pre><code class="language-bash"># ~/.bashrc</code></pre><p>inserite la dicitura:</p><pre><code class="language-bash">zsh</code></pre><p>salvate, e riavviate il terminale.</p><p><strong>Come installare ZSH (GitHub)</strong> |<a href="https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH#howto-install-zsh-in-many-platforms">&nbsp;https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH#howto-install-zsh-in-many-platforms</a></p>