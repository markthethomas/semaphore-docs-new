---
layout: post
title: Launching an SSH Session
category: The Semaphore platform
---

To launch and use an SSH session on Semaphore you need to add
a [public SSH key]() in your account settings.

After your build or deploy is finished Semaphore lets you start
an identical environment where you can run and debug your build
steps manually.

To launch such a build environment, visit the build you want to
examine and click on the Launch SSH button above your build output.

<img src="/docs/assets/img/ssh-session/create-ssh-session-1.png" class="img-responsive">

<img src="/docs/assets/img/ssh-session/create-ssh-session-2.png" class="img-responsive">

Semaphore will initialized a build machine identical to the
build you are examining, it will pull the same commit, and
export the same custom files and environment variables.

<img src="/docs/assets/img/ssh-session/create-ssh-session-3.png" class="img-responsive">

To access the started SSH session, copy the ssh command to your temrinal.
