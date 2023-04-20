```mermaid
---
title: Plan Book ER Diagram
---
erDiagram
    OutlookEvent {
        abitrary data
        uuid sticky_id
        uuid pbe_id
    }
    
    PBEntity {
        uuid oes_id 
    }

    PBImage {
        uuid pbe_id
    }

    OutlookEvent ||--|| PBEntity: has
    PBEntity ||--}o PBImage: has
```
