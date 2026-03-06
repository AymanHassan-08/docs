ls -la /mnt/okcomputer/output/app/ | head -30
total 384
-rw-r--r-- 0 root root   2986 Mar  7 05:35 MOBILE_APP_README.md
-rw-r--r-- 0 root root   2555 Mar  7 03:47 README.md
drwxr-xr-x 0 root root      0 Mar  7 05:34 android
-rw-r--r-- 0 root root    565 Mar  7 05:34 capacitor.config.ts
-rw-r--r-- 0 root root    461 Mar  7 03:47 components.json
drwxr-xr-x 0 root root      0 Mar  7 03:59 dist
-rw-r--r-- 0 root root    616 Mar  7 03:47 eslint.config.js
-rw-r--r-- 0 root root    302 Mar  7 03:47 index.html
-rw-r--r-- 0 root root   1389 Mar  7 03:47 info.md
drwxr-xr-x 0 root root      0 Mar  7 05:34 ios
drwxr-xr-x 0 root root      0 Mar  7 05:36 node_modules
-rw-r--r-- 0 root root 335235 Mar  7 05:34 package-lock.json
-rw-r--r-- 0 root root   2946 Mar  7 05:36 package.json
-rw-r--r-- 0 root root     80 Mar  7 03:47 postcss.config.js
drwxr-xr-x 0 root root      0 Mar  7 03:49 public
drwxr-xr-x 0 root root      0 Mar  7 03:47 src
-rw-r--r-- 0 root root   2777 Mar  7 03:47 tailwind.config.js
-rw-r--r-- 0 root root    815 Mar  7 03:47 tsconfig.app.json
-rw-r--r-- 0 root root    232 Mar  7 03:47 tsconfig.json
-rw-r--r-- 0 root root    653 Mar  7 03:47 tsconfig.node.json
-rw-r--r-- 0 root root    354 Mar  7 03:47 vite.config.ts
---
title: GitHub Apps overview
shortTitle: Overview
intro: 'You can use {% data variables.product.prodname_github_apps %} to extend the functionality of {% data variables.product.company_short %}.'
allowTitleToDifferFromFilename: true
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
type: overview
---

## About {% data variables.product.prodname_github_apps %}

{% data variables.product.prodname_github_apps %} are tools that extend {% data variables.product.company_short %}'s functionality. {% data variables.product.prodname_github_apps %} can do things on {% data variables.product.company_short %} like open issues, comment on pull requests, and manage projects. They can also do things outside of {% data variables.product.company_short %} based on events that happen on {% data variables.product.company_short %}. For example, a {% data variables.product.prodname_github_app %} can post on Slack when an issue is opened on {% data variables.product.company_short %}.

For more information about using {% data variables.product.prodname_github_apps %}, see [AUTOTITLE](/apps/using-github-apps/about-using-github-apps).

For more information about building {% data variables.product.prodname_github_apps %}, see [AUTOTITLE](/apps/creating-github-apps/setting-up-a-github-app/about-creating-github-apps).

## {% data variables.product.prodname_github_apps %} and {% data variables.product.prodname_oauth_apps %}

{% data variables.product.company_short %} also supports {% data variables.product.prodname_oauth_apps %}. In general, {% data variables.product.prodname_github_apps %} are preferred over {% data variables.product.prodname_oauth_apps %}. {% data variables.product.prodname_github_apps %} use fine-grained permissions, give the user more control over which repositories the app can access, and use short-lived tokens. These properties can harden the security of the app by limiting the damage that could be done if the app's credentials were leaked. For more information, see [AUTOTITLE](/apps/oauth-apps/building-oauth-apps/differences-between-github-apps-and-oauth-apps).
