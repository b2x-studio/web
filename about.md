---
layout: page
title: About
permalink: /about/
---

## What is B2X?

// todo: B2X history & diagrams

Learn about B2X: the identity construct everyone knows but is impossible to explain

## What is B2X Studio?

B2X Studio is a collection of tools, libraries, docs & experiments implementing B2X-style identity constructs using a variety of platforms. Problems to solve include global home-realm discovery, delegated administration, authorization tiering, among others. 

Today, two major platforms offer 'ecosystem' federation:
- Google
- Microsoft Azure AD (per-environment: Commercial, US Government, China, etc)

Ecosystem federation as in a single federation used to authenticate all users within that ecosystem, e.g., a user who is a member of an organzation that uses Google Workspace or Microsoft Office 365 can use their existing authentication services with Google or Microsoft to authenticate. This model doesn't require anything extra of the user, their administrators or the developer of the target software.

Contrast that with 'local' federations, where the federation for a realm is point-to-point, e.g., a user from `example.com` is authenticated by a federation service that only knows about that realm through a bespoke federation for `example.com.` Systems like ADFS, Okta, etc use this model. As a developer of cloud-delivered software, 

As more software is built and delivered by non-traditional software companies, a variety of people, identities & relationships are needed to meet requirements. 

## Demos
- [B2X AuthZ with Home Realm Discovery](https://aka.ms/b2x/signin)

## Repositories
- [B2X Administrative OpenAPI docs](https://api.admin.b2x.studio)
- [B2X Admin API](https://github.com/jpda/b2c-approles)
- [B2X Runtime API](https://github.com/jpda/b2c-approles)

## Contacts
- [info@b2x.studio](mailto:info@b2x.studio)
- [twitter](https://twitter.com/@azureandchill)
- [github](https://github.com/jpda)