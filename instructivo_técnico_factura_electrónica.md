# Instructivo Técnico Factura Electrónica

## Actividades Previas a la Emisión de Documentos

```mermaid
sequenceDiagram

    actor       Contribuyente as Contribuyente<br/>Emisor
    participant SII

    Note left of Contribuyente: Enrolamiento

    Contribuyente->>SII: fecha de autorización<br/>los tipos de documentos electrónicos autorizados<br/>identificación del Usuario-Administrador<br/>e-mail contribuyentes autorizados
    activate SII
    
    SII->>Contribuyente: Entrega archivo "Código de Autorización de Folios (CAF)"
    deactivate SII

```




Fuente [https://www.sii.cl/factura_electronica/factura_mercado/instructivo_emision.pdf](https://www.sii.cl/factura_electronica/factura_mercado/instructivo_emision.pdf)




