---
layout: default
title: Suppressed
parent: Aardvark Schema
nav_order: 39
---

## Suppressed

| Label                 | Suppressed                                                                                                                                                                              |
|:----------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Aardvark-id           | 39                                                                                                                                                                                      |
| URI                   | `gbl_suppressed_b`                                                                                                                                                                      |
| Obligation            | Optional                                                                                                                                                                                |
| Multiplicity          | 0-1                                                                                                                                                                                     |
| Field type            | string boolean                                                                                                                                                                          |
| Purpose               | To hide items from users in the search results. If set to True, the record will not appear in search results. It is still accessible from the Data Relations widget and via direct URL. |
| Entry Guidelines      | Only one of two values are allowed: true or false.                                                                                                                                      |
| Commentary            | This field is useful for multipart items with identical metadata, such as pages in an atlas or series.                                                                                  |
| Controlled Vocabulary | yes - strict                                                                                                                                                                            |
| Example value         | true                                                                                                                                                                                    |
| Element Set           | GBL                                                                                                                                                                                     |
| Group                 | Administrative                                                                                                                                                                          |
