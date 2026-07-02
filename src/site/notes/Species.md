---
{"dg-publish":true,"permalink":"/species/","dg-note-properties":{}}
---

# Quick overview

```base
views:
  - type: table
    name: Table
  - type: table
    name: Species
    filters:
      and:
        - Related.contains("species")
    order:
      - file.name
      - Spark
      - Fade
    columnSize:
      note.Spark: 204

```

