[POST: /api/v2.0/comprobantes/comprobantes-retencion](#)
Comprobante de retención electrónico utilizando versión 2.0.0 del SRI.
```json
{
    "version": "2.0.0",
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
    "docsSustento": [
        {
            "codSustento": "01",
            "codDocSustento": "01",
            "numDocSustento": "002001000000112",
            "fechaEmisionDocSustento": "23/12/2022",
            "fechaRegistroContable": "23/12/2022",
            "numAutDocSustento": "2312202201171174933100120020010000001126813706510",
            "pagoLocExt": "01",
            "tipoRegi": null,
            "paisEfecPago": null,
            "aplicConvDobTrib": null,
            "pagExtSujRetNorLeg": null,
            "pagoRegFis": null,
            "impuestoDocSustento": [
                {
                    "codImpuestoDocSustento": "2",
                    "codigoPorcentaje": "2",
                    "baseImponible": 88.95,
                    "tarifa": 12
                }
            ],
            "retencion": [
                {
                    "codigo": "2",
                    "codigoRetencion": "2",
                    "baseImponible": 10.67,
                    "porcentajeRetener": 70.00
                },
                {
                    "codigo": "1",
                    "codigoRetencion": "304",
                    "baseImponible": 88.95,
                    "porcentajeRetener": 8.00
                }
            ],
            "pago": [
                {
                    "formaPago": "20",
                    "total": 99.62,
                    "plazo": "",
                    "unidadTiempo": ""
                }
            ]
        }
    ],
    "campoAdicional": [
        {
            "nombre": "Email",
            "value": "pruebas@veronica.ec"
        }
    ]
}
 ```