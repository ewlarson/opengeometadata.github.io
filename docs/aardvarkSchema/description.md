---
layout: default
title: Description
parent: Aardvark Schema
nav_order: 3
---

## Description

| Label                 | Description             |
|:----------------------|:------------------------|
| Aardvark-id           | 03                      |
| URI                   | `dct_description_sm`    |
| Obligation            | Recommended             |
| Multiplicity          | 0-\*                    |
| Field type            | string                  |
| Purpose               | To provide the user with a summary of the resource |
| Entry Guidelines      | At minimum, this is a reiteration of the title in sentence format. Other relevant information, such as data creation methods, data sources, and special licenses, may also be included. Description is a plain text field by default. |
| Commentary            | This field is the second-most prominent value (after [Title](https://opengeometadata.github.io/docs/aardvarkSchema/title)) that users see when search or browsing for items. Although not required, it is strongly recommended. If the description is minimal or lacking, it can be improved by concatenating available metadata fields, such as title, date, format, and place. This is a plain text field, so html code is not supported here unless the application is customized. |
| Controlled Vocabulary | no                      |
| Example value         | "This polygon shapefile represents boundaries of election districts in New York City. It was harvested from the NYC Open Data Portal." |
| Element Set           | DCMI                    |
| Group                 | Bibliographic - general |
