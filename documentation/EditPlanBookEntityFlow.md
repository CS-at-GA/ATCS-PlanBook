```mermaid
---
title: Edit a Planbook Entity (from app or web)
---
flowchart TD
    e(Planbook Entity)
    subgraph edit
    e --> changes{{make changes}}
    changes --> time{changing time?}
    time-- yes --> getOE{{get Outlook Event}}
    time-- no --> finalize
    getOE --> OE
    OE-- update time --> finalize
    end
    azure-- retrieve --> e
    finalize-- store Planbook entity in --> azure
    finalize-- store Outlook entity in --> outlook
    outlook -- retrieve --> getOE
    outlook[(Outlook)]
    azure[(azure)]
 ```
