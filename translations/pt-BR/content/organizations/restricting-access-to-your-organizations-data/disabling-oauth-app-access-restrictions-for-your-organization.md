---
title: Desabilitar restrições de acesso do aplicativo OAuth da sua organização
intro: Os proprietários da organização podem desabilitar as restrições em {% data variables.product.prodname_oauth_apps %} que têm acesso aos recursos da organização.
redirect_from:
- /articles/disabling-third-party-application-restrictions-for-your-organization
- /articles/disabling-oauth-app-access-restrictions-for-your-organization
- /github/setting-up-and-managing-organizations-and-teams/disabling-oauth-app-access-restrictions-for-your-organization
versions:
  fpt: '*'
  ghec: '*'
topics:
- Organizations
- Teams
shortTitle: Disable OAuth App
ms.openlocfilehash: 41fae63d8d491eec7a6cd6a275958d5c96fb5f5c
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "145128293"
---
{% danger %}

**Aviso**: com a desabilitação das restrições de acesso do {% data variables.product.prodname_oauth_app %} da sua organização, qualquer integrante da organização autorizará automaticamente o acesso do {% data variables.product.prodname_oauth_app %} aos recursos privados da organização ao aprovar um aplicativo para ser usado nas configurações de conta pessoal dele.

{% enddanger %}

{% data reusables.profile.access_org %} {% data reusables.profile.org_settings %} {% data reusables.organizations.oauth_app_access %}
5. Clique em **Remover restrições**
  ![Botão para remover restrições](/assets/images/help/settings/settings-third-party-remove-restrictions.png)
6. Depois de revisar as informações sobre desabilitação de restrições de aplicativos de terceiros, clique em **Yes, remove application restrictions** (Sim, remover restrições de aplicativos).
  ![Botão para remover confirmação](/assets/images/help/settings/settings-third-party-confirm-disable.png)
