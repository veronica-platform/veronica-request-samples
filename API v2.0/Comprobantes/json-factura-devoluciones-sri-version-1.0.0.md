[POST: /api/v2.0/comprobantes/facturas](#)
Factura electrónica de devolución.
```json
{
    "version": "1.0.0",
    "fechaEmision": "30/03/2021",
    "codDoc": "01",
    "ruc": "XXXXXXXXXXXXX",
    "estab": "001",
    "ptoEmi": "001",
    "secuencial": "000003519",
    "receptor": {
        "tipoIdentificacion": "04",
        "identificacion": "9999999999999",
        "razonSocial": "PRUEBAS UNITARIAS - VERONICA - RAZÓN SOCIAL",
        "direccion": "PRUEBAS UNITARIAS - VERONICA - DIRECCIÓN PRINCIPAL",
        "propina": 0
    },
    "detalles": [
        {
            "codigoPrincipal": "1000",
            "codigoAuxiliar": "0",
            "cantidad": 1.000000,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 382.760000,
            "descuento": 0.00,
            "detAdicional": [],
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "0",
                    "tarifa": 0
                }
            ]
        }
    ],
    "moneda": "DOLAR",
    "reembolsoDetalle": [
        {
            "tipoIdentificacionProveedorReembolso": "04",
            "identificacionProveedorReembolso": "1792711975001",
            "codPaisPagoProveedorReembolso": "593",
            "tipoProveedorReembolso": "02",
            "codDocReembolso": "01",
            "estabDocReembolso": "001",
            "ptoEmiDocReembolso": "002",
            "secuencialDocReembolso": "000000034",
            "fechaEmisionDocReembolso": "15/06/2022",
            "numeroAutorizacionDocReemb": "1506202201179271197500120010020000000341234567811",
            "detalleImpuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12,
                    "baseImponibleReembolso": 177.00000
                }
            ]
        },
        {
            "tipoIdentificacionProveedorReembolso": "04",
            "identificacionProveedorReembolso": "1792711975001",
            "codPaisPagoProveedorReembolso": "593",
            "tipoProveedorReembolso": "02",
            "codDocReembolso": "01",
            "estabDocReembolso": "001",
            "ptoEmiDocReembolso": "002",
            "secuencialDocReembolso": "000000034",
            "fechaEmisionDocReembolso": "15/06/2022",
            "numeroAutorizacionDocReemb": "1506202201179271197500120010020000000341234567811",
            "detalleImpuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12,
                    "baseImponibleReembolso": 164.75000
                }
            ]
        }
    ],
    "pagos": [
        {
            "formaPago": "20",
            "total": 382.76,
            "plazo": "",
            "unidadTiempo": ""
        }
    ],
    "campoAdicional": [
        {
            "nombre": "Descripción",
            "value": "REEMBOLSO COMBUSTIBLE"
        }
    ]
}
 ```