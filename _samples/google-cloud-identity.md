---
title: 'Google Cloud Identity APIs'
subtitle: Developer Guides | Reference Documentation | Python
date: 2021-03-31
description: Developer guides, reference documentation, Python scripting
featured_image: '/images/ci-apis.png'
---

I wrote the following overviews and developer guides for this product:

+	[Groups API overview](https://cloud.google.com/identity/docs/groups)
+	[Dynamic groups overview](https://cloud.google.com/identity/docs/concepts/overview-dynamic-groups)
+	[User Invitation API overview](https://cloud.google.com/identity/docs/concepts/overview-user-invitations)
+	[Querying group memberships](https://cloud.google.com/identity/docs/how-to/query-memberships)
+	[Managing membership expirations](https://cloud.google.com/identity/docs/how-to/manage-expirations)

The Cloud Identity [setup guide](https://cloud.google.com/identity/docs/set-up-cloud-identity-admin) and [domain verification guides](https://cloud.google.com/identity/docs/verify-domain) are assembled by a Python script that scrapes the content from the corresponding articles in the Cloud Identity admin help center. The script was broken when I inherited the product, and I fixed and documented it so that the documenation sites could be kept in sync easily and without duplication.