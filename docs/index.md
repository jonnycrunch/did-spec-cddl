---
layout: respec
title: Concise Data Definition Language for the DID Spec Registeries
respec: >
  {
    "name": "DID Spec CDDL",
    "status": "CG-DRAFT",
    "latest": "https://transendx.github.io/did-core-cddl/spec/latest",
    "repository": "https://github.com/transendx/did-core-cddl",
    "issues": "https://github.com/transendx/did-core-cddl/issues",
    "group": {
      "name": "Decentralized Identifers Work Group",
      "url": "https://www.w3.org/community/credentials/",
      "list": "public-credentials",
      "patentUri": "https://www.w3.org/community/about/agreements/cla/"
    },
    "editors": [
      {
        "name": "Jonathan Holt, DO, MS",
        "url": "https://example.com",
        "company": "TranSendX",
        "companyURL": "https://transendx.com"
      }
    ],
    "bibliography": {
      "RFC7049": {
        "title": "Concise Binary Object Representation (CBOR)",
        "href": "https://tools.ietf.org/html/rfc7049",
        "authors": ["C. Bormann" "P. Hoffman" ],
        "status": "Standards Track",
        "publisher": "Internet Engineering Task Force (IETF)"
      }
    }
  }
---

<section id="abstract">
  <p>
    Your specification abstract goes here.
  </p>
</section>

<section id="sotd">
  <p>
    This is an experimental specification and is undergoing regular
    revisions. It is not fit for production deployment.
  </p>
</section>

<section id="terminology">
  <h2>Terminology</h2>
  <p>
    Your specification terminology goes here.
  </p>
</section>

<style>
.red43 {
  color: red;
}
</style>

<p class="red43">Custom CSS is Supported!</p>

## Markdown is Supported !

<p>
Example link to bibliography here... [[RFC7049]].
</p>

#### Example:

```json
{
  "id": "did:example:123#key-0",
  "controller": "did:example:123",
  "type": "JsonWebKey2020",
  "publicKeyJwk": {
    "crv": "secp256k1",
    "kty": "EC",
    "x": "dWCvM4fTdeM0KmloF57zxtBPXTOythHPMm1HCLrdd3A",
    "y": "36uMVGM7hnw-N6GnjFcihWE3SkrhMLzzLCdPMXPEXlA"
  }
}
```

<section data-dfn-for="Foo" data-link-for="Foo">
  <h2>Start your spec!</h2>
  <pre class="idl">
  interface Foo {
    attribute Bar bar;
    undefined doTheFoo();
  };
  </pre>
  <section>
    <h2><dfn>bar</dfn> attribute</h2>
    <p>When getting, the <a>bar</a> attribute returns you a 🍹.</p>
  </section>
  <section>
    <h2><dfn>doTheFoo(DOMString thing)</dfn> method</h2>
    <p>When called, <code>doTheFoo(<var>thing</var>)</code> it MUST behave as follows:</p>
    <ol class="algorithm">
      <li>If <var>thing</var>....</li>
      <li>Let <var>someProp</var>... of the [[!DOM]] spec.</li>
    </ol>
  </section>
</section>

<section id='conformance'>
  <!-- This section is filled automatically by ReSpec. -->
</section>
