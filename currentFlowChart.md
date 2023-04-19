```mermaid
graph TD
    odb
    pbedb
    odb --> oe
    oe --> app
    oe --> web
    oe --> outlook
    app --> oe
    web --> oe
    outlook --> oe
    oe --> odb
    pbedb --> pbe
    pbe --> app
    pbe --> web
    app --> pbe
    web --> pbe
    pbe --> pbedb
```
