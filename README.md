[[_TOC_]]


# SII-UML

Documentación UML no oficial sobre temas del SII de Chile.



* [https://mermaid.js.org](https://mermaid.js.org)
* [https://www.sii.cl/](https://www.sii.cl/)


```mermaid
sequenceDiagram

    actor       Contribuyente as "Contribuyente<br/>Emisor"
    participant SII

    Contribuyente->>SII: Solicita folios
    activate SII
    
    SII->>Contribuyente: Entrega archivo "Código de Autorización de Folios (CAF)"
    deactivate SII


```

