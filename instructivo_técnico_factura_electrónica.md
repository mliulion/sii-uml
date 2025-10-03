# Instructivo Técnico Factura Electrónica

CAF = Código de Autorización de Folios
DTE = Documento Tributario Electrónico


## Actividades Previas a la Emisión de Documentos

```mermaid
sequenceDiagram

    actor       Representante as Representante<br/>Legal
    actor       Administrador as Usuario-Administrador
    actor       Firmante as Firmante<br/>Autorizado
    participant SII

    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

    Note left of Representante: Enrolamiento

    Representante->>SII: Identificación del Usuario-Administrador
    activate SII

    Note over SII: Registra:<br/>- Fecha de autorización<br/>- Tipos de documentos electrónicos autorizados<br/>- Identificación del Usuario-Administrador<br/>- E-mail para intercambio de información con otros contribuyentes autorizados

    SII-->>Representante:
    deactivate SII

    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

    Note left of Representante: Autorización de Firmantes

    Administrador->>SII: Firmantes autorizados al interior de la empresa
    activate SII
    SII-->>Administrador:
    deactivate SII

    Firmante->>SII:  Solicita números de folios para generar DTEs válidos

    Administrador->>SII:  Solicitar la anulación de folios previamente autorizados

    Firmante->>SII:  Firmar documentos tributarios electrónicos
    Firmante->>SII:  Enviar documentos emitidos al SII

    Note over Representante: Adquiere certificados digitales para los firmantes autorizados

    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

    Note left of Representante: Obtención de rango de folios autorizados y Código de Autorización de Folios
    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

    Note left of Representante: Verificaciones al "Código de Autorización de Folios"



```




Fuente [https://www.sii.cl/factura_electronica/factura_mercado/instructivo_emision.pdf](https://www.sii.cl/factura_electronica/factura_mercado/instructivo_emision.pdf)




