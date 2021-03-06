---
title: GoodCop API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

toc_footers:
  - <a href='#'>GoodCop Api Documentation</a>
  - <a href=''>Documentation by CloudCover</a>

includes:
  - user
  - group
  - product
  - tenant
  - api
  - auth
  - errors
  

search: true
---

# API Reference

The GoodCop API is organized around REST. Our API has resource-oriented URLs, and uses HTTPS response codes to indicate API errors. We use built-in HTTPS features, like HTTPS authentication and HTTPS verbs, which are understood by off-the-shelf HTTPS clients. JSON is returned by all API responses, including errors.


# Authentication

> To authorize, use this code:

```shell
> Example Request
curl "api_endpoint_here"
  -H "Authorization: test_aIsKmHDTaSvYJGHGHJ5_QsnJZ4UWJFwMgt5AIA4Oyvs="
```

> Make sure to replace Authorization header with your Product API key.

Authenticate your account when using the API by including your Product API key in the request.
GoodCop expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: test_aIsKmHDTaSvYJGHGHJ5_QsnJZ4UWJFwMgt5AIA4Oyvs=`

<aside style="background:#5bc0de;">
You must replace <code style="#000000;">test_aIsKmHDTaSvYJGHGHJ5_QsnJZ4UWJFwMgt5AIA4Oyvs=</code> with your product API key.
</aside>