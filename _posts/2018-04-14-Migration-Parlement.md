---
layout: post
title: Migration du Parlement
---

En suivant les instructions fournies pas Eden

## Contents
Tout le contenu uploadé (images/photos/enregistrements): récupération par ftp depuis ftp.orchestrerie.com:/parlement/wp-content/uploads

    lftp ftp.orchestrerie.com
    cd parlement/wp-content/uploads
    mirror . uploads

![lftp]({{ site.baseurl }}/images/lftp.png)

