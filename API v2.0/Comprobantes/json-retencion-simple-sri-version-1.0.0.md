[POST: /api/v2.0/comprobantes/comprobantes-retencion](#)
Comprobante de retención electrónico utilizando versión 1.0.0 del SRI.
```json
{
    "version": "1.0.0",
    "fechaEmision": "28/04/2022",
    "codDoc": "07",
    "ruc": "XXXXXXXXXXXXX",
    "estab": "001",
    "ptoEmi": "001",
    "secuencial": "000000001",
    "receptor": {
        "tipoIdentificacion": "04",
        "identificacion": "9999999999999",
        "razonSocial": "PRUEBAS UNITARIAS - VERONICA - RAZÓN SOCIAL",
        "periodoFiscal": "05/2022",
        "parteRel": "SI",
        "tipoSujetoRetenido": null
    },
    "impuestos": [
        {
            "codigo": "1",
            "codigoRetencion": "332",
            "baseImponible": 98.00,
            "porcentajeRetener": 1.75,
            "codDocSustento": "01",
            "numDocSustento": "001004000037261",
            "fechaEmisionDocSustento": "27/12/2022"
        },
        {
            "codigo": "2",
            "codigoRetencion": "1",
            "baseImponible": 11.76,
            "porcentajeRetener": 30,
            "codDocSustento": "01",
            "numDocSustento": "001004000037261",
            "fechaEmisionDocSustento": "27/12/2022"
        }
    ],
    "campoAdicional": [
        {
            "nombre": "Email",
            "value": "Pruebas veronica"
        }
    ]
}
 ```