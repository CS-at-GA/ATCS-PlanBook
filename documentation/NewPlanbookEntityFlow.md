```mermaid
---
title: Create a Planbook Entity (from app or web)
---
flowchart TD
    new(New Planbook Entity)
    subgraph create
    newOE(New Outlook Event)
    new --> time{{define time}}
    new --> content{{create content}}
    new --> id{{create id}}
    content --> image{{handwriting}}
    time --> newOE
    newOE --> oeid{{create sticky outlook id}}
    id-- add to Outlook event --> newOE
    end
    newOE-- store  in --> outlook
    create-- store in --> azure
    outlook[(Outlook)]
    azure[(azure)]
 ```
