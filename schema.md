Database Schema
===============

This is a schema for the database. Feel free to edit it. All data should be dummy data. To update the table of contents automatically, run `doctoc schema.md`.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Database Schema](#database-schema)
    - [Paper](#paper)
    - [Highlight](#highlight)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### Paper

```json
{
  "title": "This is an example title",
  "publication": {
    "id": "000000",
    "author": [
      {
        "email": "test@gmail.com",
        "department": "Physics",
        "graph": "images/graph.png",
        "name": "Richard Feynman",
        "photo": "http://upload.wikimedia.org/wikipedia/en/4/42/Richard_Feynman_Nobel.jpg",
        "publications": [
          "Lectures on Physics 1",
          "Lectures on Physics 2",
          "Lectures on Physics 3"
        ],
        "university": "CIT",
        "website": "#website"
      },
      {
        "email": "test@gmail.com",
        "department": "Linguistics",
        "graph": "images/graph.png",
        "name": "Noam Chomsky",
        "photo": "https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Chomsky.jpg/460px-Chomsky.jpg",
        "publications": [
          "Lectures on Physics 1",
          "Lectures on Physics 2",
          "Lectures on Physics 3"
        ],
        "university": "CIT",
        "website": "#website"
      }
    ],
    "title": "Rapid prototyping of 3D DNA-origami shapes with caDNAno",
    "journal": "Nucleic acids research 37 (15), 5001",
    "issue": "2.1",
    "doi": "10.1093/nar/gkp436",
    "toc": [
      {
        "id": 1,
        "name": "Introduction",
        "anchor": "#intro"
      },
      {
        "id": 2,
        "name": "1st Section",
        "anchor": "#section1"
      },
      {
        "id": 3,
        "name": "Conclusion",
        "anchor": "#conclusion"
      }
    ],
    "cited_by": [
      "Lectures on Physics 1",
      "Lectures on Physics 2",
      "Lectures on Physics 3"
    ],
    "cites": [
      "Lectures on Physics 4",
      "Lectures on Physics 5",
      "Lectures on Physics 6"
    ],
    "related": [
      "Lectures on Physics 7",
      "Lectures on Physics 8",
      "Lectures on Physics 9"
    ],
    "cited_by_tweeters_count": "9001",
    "subjects": ["tag1", "tag2"]
  }
}
```

### Highlight

```json
{
  "selections": [
    {
      "text": "The InterPlanetary File System (IPFS) is a peer-to-peer dis-tributed \fle system that seeks to connect all computing de-vices  with  the  same  system  of  \fles. ",
      "id": "250dd0f4c3ba5f832c031d90bb4db2e0ea0c98d6",
      "url": "http://static.benet.ai/t/ipfs.pdf",
      "documentId": "aef21fa9e7177203dc5b8ae74c136b",
      "pdfCoords": {
        "page": 0,
        "coords": [
          [
            53.7890625,
            567.59765625,
            292.89697265625,
            558.59765625
          ],
          [
            53.7890625,
            557.1328125,
            290.3189392089844,
            548.1328125
          ],
          [
            53.7890625,
            557.1328125,
            290.3173828125,
            548.1328125
          ],
          [
            53.7890625,
            546.6679687500001,
            290.4957275390625,
            537.6679687500001
          ],
          [
            53.7890625,
            546.6679687500001,
            201.5793228149414,
            537.6679687500001
          ]
        ]
      },
      "htmlCoords": {
        "height": 39.90625,
        "width": 318.810546875,
        "left": 231.71875,
        "bottom": 374.109375,
        "right": 550.529296875,
        "top": 334.203125
      }
    },
    ...
  ],
  "_id": "aef21fa9e7177203dc5b8ae74c136b",
  "_rev": "15-31c7a0208e291017d6df428eadd3b02b"
}
```