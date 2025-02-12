---
layout: default
title: References
parent: Aardvark Schema
nav_order: 34
---

## References

| Label                 | References                                                                                                                                                                                                       |
|:----------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Aardvark-id           | 34                                                                                                                                                                                                               |
| URI                   | `dct_references_s`                                                                                                                                                                                               |
| Obligation            | Recommended                                                                                                                                                                                                      |
| Multiplicity          | 0-1                                                                                                                                                                                                              |
| Field type            | string JSON                                                                                                                                                                                                      |
| Purpose               | To provide external URLs for accessing or describing the resource                                                                                                                                                |
| Entry Guidelines      | This field defines external services and references using the CatInterOp approach. The field value is a serialized JSON array of key/value pairs, with keys representing XML namespace URI's and values the URL. |
| Commentary            | All of the external links for the resource are added to This field as a serialized JSON array of key/value pairs. The download key/value pair is unique, because the value can be an array.                      |
| Controlled Vocabulary | no                                                                                                                                                                                                               |
| Example value         | ```"dct_references_s": "{```<br>```\"http://schema.org/url\":\"http://purl.stanford.edu/bm662dm5913\",```<br>```\"http://schema.org/downloadUrl\":\"http://stacks.stanford.edu/file/druid:bm662dm5913/data.zip```<br>```\"}"```                      |
| Element Set           | DCMI                                                                                                                                                                                                             |
| Group                 | Distribution                                                                                                                                                                                                     |
