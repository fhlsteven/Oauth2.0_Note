# OAuth 2.0 授权框架

## Abstract

>## 摘要

The OAuth 2.0 authorization framework enables a third-party application to obtain limited access to an HTTP service, either on behalf of a resource owner by orchestrating an approval interaction between the resource owner and the HTTP service, or by allowing the third-party application to obtain access on its own behalf.  This specification replaces and obsoletes the OAuth 1.0 protocol described in RFC 5849.

> OAuth 2.0授权框架使第三方应用程序能够获得对HTTP服务的有限访问权限，代表资源所有者通过编排资源所有者和HTTP服务之间的批准交互，或允许第三方应用程序代表自己获取访问权限。此规范取代并废弃RFC 5849中描述的OAuth 1.0协议。

Status of This Memo

   This is an Internet Standards Track document.

   This document is a product of the Internet Engineering Task Force
   (IETF).  It represents the consensus of the IETF community.  It has
   received public review and has been approved for publication by the
   Internet Engineering Steering Group (IESG).  Further information on
   Internet Standards is available in Section 2 of RFC 5741.

   Information about the current status of this document, any errata,
   and how to provide feedback on it may be obtained at
   `http://www.rfc-editor.org/info/rfc6749`.

Copyright Notice

   Copyright (c) 2012 IETF Trust and the persons identified as the
   document authors.  All rights reserved.

   This document is subject to BCP 78 and the IETF Trust's Legal
   Provisions Relating to IETF Documents
   (`http://trustee.ietf.org/license-info`) in effect on the date of
   publication of this document.  Please review these documents
   carefully, as they describe your rights and restrictions with respect
   to this document.  Code Components extracted from this document must
   include Simplified BSD License text as described in Section 4.e of
   the Trust Legal Provisions and are provided without warranty as
   described in the Simplified BSD License.
  
---

## Table of Contents

  > ## 目录

1. Introduction

* 1.1. Roles 
* 1.2. Protocol Flow
* 1.3. Authorization Grant
  * 1.3.1. Authorization Code
  * 1.3.2. Implicit
  * 1.3.3. Resource Owner Password Credentials
  * 1.3.4. Client Credentials
* 1.4. Access Token
* 1.5. Refresh Token
* 1.6. TLS Version
* 1.7. HTTP Redirections
* 1.8. Interoperability
* 1.9. Notational Conventions

2. Client Registration
