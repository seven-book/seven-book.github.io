---
layout: post
title: "FreeSWITCH代码库地址更新"
tags:
  - "更新"
---

从2014年10月底，FreeSWITCH代码库改为由stash管理，该管理工具能更好地与jira集成。

如果你以前已经Clone了代码，请做如下更新：

    git remote set-url origin https://freeswitch.org/stash/scm/fs/freeswitch.git

否则的话，直接用以下地址进行克隆：

    git clone https://freeswitch.org/stash/scm/fs/freeswitch.git
