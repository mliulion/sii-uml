[[_TOC_]]


# SII-UML

Documentación UML no oficial sobre temas del SII de Chile.



* [https://mermaid.js.org](https://mermaid.js.org)
* [https://www.sii.cl/](https://www.sii.cl/)


```mermaid
sequenceDiagram
    actor       "Contribuyente\nEmisor" as Contribuyente
    participant SII

    Alice->>Bob: Hola Bob, ¿cómo estás?
    Bob-->>Alice: Todo bien, gracias
    Contribuyente ->> SII : Solicita folios
    activate SII
    SII ->> Contribuyente : Entrega archivo "Código de Autorización de Folios (CAF)"
    deactivate SII


```

