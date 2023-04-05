---
layout: post
title: "Installing System Center Operations Manager (SCOM) 2019 when security has you down"
date: 2023-04-05 09:00:00 -0500
categories: install-guide
tags: scom tls1.2 windows sql
image:
  path: /assets/img/headers/home-modern.jpg
---

So you want to install SCOM 2019 in a secure environment? This post will get you most of the way there.


# Servers

## Server Certificates
## Enforcing TLS 1.2

 `enforce_TLS.ps1`

```powershell

Get-InsertTLSCodeHere

```

# Software Downloads

# Installing Microsoft SQL Server

# Installing Operations Manager Console + Web Console

# Installing Report Server

## Links

https://www.souravmahato.com/how-to-enable-tls-1-2-in-scom/

https://kevinholman.com/2018/05/06/implementing-tls-1-2-enforcement-with-scom/


https://learn.microsoft.com/en-us/system-center/scom/plan-security-tls12-config?view=sc-om-2022

https://github.com/thekevinholman/TLS1.2Enforce