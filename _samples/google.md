---
title: 'Google'
subtitle: Developer Guides | Reference Documentation | Python
date: 2022-11-01
description: Developer guides, reference documentation, scripting, and code samples
featured_image: '/images/forms-api.png'
---

## Cloud Identity APIs

I wrote the following overviews and developer guides for this product:

+	[Groups API overview](https://cloud.google.com/identity/docs/groups)
+	[Dynamic groups overview](https://cloud.google.com/identity/docs/concepts/overview-dynamic-groups)
+	[Querying group memberships](https://cloud.google.com/identity/docs/how-to/query-memberships)
+	[Managing membership expirations](https://cloud.google.com/identity/docs/how-to/manage-expirations)
+	[User Invitation API overview](https://cloud.google.com/identity/docs/concepts/overview-user-invitations)
+   [Creating and managing user invitations](https://cloud.google.com/identity/docs/how-to/manage-user-invitations)

The Cloud Identity [setup guide](https://cloud.google.com/identity/docs/set-up-cloud-identity-admin) and [domain verification guides](https://cloud.google.com/identity/docs/verify-domain) are assembled by a Python script that scrapes the content from the corresponding articles in the Cloud Identity admin help center. The script was broken when I inherited the product, and I fixed and documented it so that the documenation sites could be kept in sync easily and without duplication.

## Google Forms API

I wrote the overview and main developer guides:

+	[Overview](https://developers.google.com/forms/api/guides)
+	[Create a form or quiz](https://developers.google.com/forms/api/guides/create-form-quiz)
+	[Update a form or quiz](https://developers.google.com/forms/api/guides/update-form-quiz)
+	[Set up quiz grading options](https://developers.google.com/forms/api/guides/setup-grading)
+	[Retrieve forms and responses](https://developers.google.com/forms/api/guides/retrieve-forms-responses)

I also built and tested most of the Python code samples based on create/retrieve samples created by Engineering, and edited all [reference documentation](https://developers.google.com/forms/api/reference/rest/v1/forms) for site style and clarity.

