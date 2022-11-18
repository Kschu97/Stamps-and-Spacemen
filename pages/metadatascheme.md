---
title: Metadata Scheme
layout: about
permalink: /metadatascheme.html
---

{% include feature/jumbotron.html objectid="https://www.nasa.gov/sites/default/files/thumbnails/image/main_image_star-forming_region_carina_nircam_final-5mb.jpg" %}

## Metadata Scheme

| Name(s) | DC mapping |	Obligation |	Cardinality |	Visible to users? |	Description |
|--|--|--|--|--|--|
| Title |	Title |	Required	| 1 or more |	Yes |	Title of the work |
| Objectid |	Identifier |	Required |	1 | 	No |	Unique identifier of the resource |
| Country |	Creator	| Required |	1 or more |	Yes |	Creator of the work |
| Date |	Date |	Required |	1 |	Yes |	Date of publication |
| Format; Size |	Format |	Required |	2	| Yes |	Describes file format; gives dimensions of stamps in mm. |
| Series |	Type |	Required |	1	| Yes |	Series stamp belongs to |
| Subject |	Subject |	Required |	1 or more	| Yes |	Subject Stamp deals with |
| Location; Longitude; Latitude; date_is_approximate |	Coverage |	Required |	4 |	Yes	| Country that issued the stamp; longitude; latitude; approximate date (if actual date is not known) |
| Description	| Description |	Optional |	1	| Yes |	A description of the stamp |
| Language |	Language |	Optional	| 1 or more |	Yes	| The language(s) on the stamp |
| Type |	Type |	Required	| 1 |	Yes |	The nature or genre of the resource e.g. still image |
| Rights; Rights statement |	Rights	| Required |	2	 | Yes |	Rights statement |
| Source |	Source |	Required |	1	| Yes |	Where the item is derived |
