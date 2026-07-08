# Blue is Blue

## Index{#index}

- [Diagrama del caso](#diagrama)
- [Acabádlo](./escenas/wrap-it.md)
- [Al rojo vivo](./escenas/all-fired-up.md)
    - [Entrevistando a Lynn](./escenas/all-fired-up.md#interview)
    - [Presionando a Parson](./escenas/all-fired-up.md#pressuring)
- [Caso Glitch](./escenas/glitch.md)
- [Cold Case](./escenas/cold-case.md)
- [El ataque de la araña](./escenas/spider-attack.md)
    - [Files](./escenas/cold-case.md#files)
- [El Manitas](./escenas/the-fixer.md)
    -[Reunión con Shandell](./escenas/the-fixer.md#meeting)
- [Fake News](./escenas/fake-news.md)
- [Instituto Quade](./escenas/instituto-quade.md)
    - [Archivos de investigación](./escenas/instituto-quade.md#files)
    - [Miranda Gaushell](./escenas/instituto-quade.md#gaushell)
- [Interrogando a Angie](./escenas/interrogation.md)
- [La Gran Mentira](./escenas/the-big-lie.md)
- [Resolviendo el caso](./clearing.md)
- [Sins of the Helix](./escenas/sins-of-helix.md#sins)
    - [Angie Arrestada](./escenas/sins-of-helix.md#angieArrested)
    - [Deteniendo a Angie](./escenas/sins-of-helix.md#angieDown)
    - [Flashback](./escenas/sins-of-helix.md#flash)
- [Typhoid Mary](./escenas/typhoid-mary.md)
- [Viuda](./escenas/viuda.md)
    - [La versión de Danica](./escenas/viuda.md#danicaAccount)
    - [El garaje](./escenas/viuda.md#parking)


## Diagrama{diagrama}
[Índice](#index)
```mermaid
flowchart TD


classDef definitivas fill:#dbeafe,stroke:#2563eb,color:#000
classDef core fill:#dcfce7,stroke:#16a34a,color:#000
classDef alternate fill:#fef3c7,stroke:#ca8a04,color:#000
classDef hazard fill:#fecaca,stroke:#dc2626,color:#000


    Intro[Sins Of Helix]:::definitivas
    Intro --> Cold[Cold Case]:::core

    Cold --> Interrogar[Interrogando a Angie]:::alternate
    Cold --> Viuda[La viuda]:::core
    Cold --> Insti[Instituto Quade]:::alternate

    Viuda --> Glitch[Caso Glitch]:::core
    Viuda --> Insti
    Viuda --> Sandra[Typhoid Mary]:::core

    Fake[Fake News]:::hazard
    Fake --> Acabad[Acabadlo]:::definitivas

    Insti --> Sandra
    Insti --> Lynn[All Fired Up]:::core
    Insti --> Glen[The Spider]:::alternate
    Insti --> Malcom[The Fixer]:::core
    Insti --> Glitch

    Interrogar --> Glen
    Interrogar --> Sandra

    Sandra --> Lynn

    Lynn--> Malcom

    Glen --> Araña[El ataque de la araña]:::hazard

    Malcom --> Lie[La Gran Mentira]:::definitivas
    Malcom --> Resolve[Resolviendo el caso]:::definitivas


```
  