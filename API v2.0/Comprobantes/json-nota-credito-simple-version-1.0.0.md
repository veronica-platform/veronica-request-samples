[POST: /api/v2.0/comprobantes/notas-credito](#)
Nota de crédito electrónica con un único detalle.
```json
{
    "version": "1.0.0",
    "fechaEmision": "28/04/2022",
    "codDoc": "04",
    "ruc": "XXXXXXXXXXXXX",
    "estab": "001",
    "ptoEmi": "001",
    "secuencial": "000000001",
    "receptor": {
        "tipoIdentificacion": "04",
        "identificacion": "9999999999999",
        "razonSocial": "PRUEBAS UNITARIAS - VERONICA - RAZÓN SOCIAL",
        "direccion": "PRUEBAS UNITARIAS - VERONICA - DIRECCIÓN PRINCIPAL",
        "propina": 0
    },
    "codDocModificado": "01",
    "numDocModificado": "001-001-000288720",
    "fechaEmisionDocSustento": "19/04/2022",
    "motivo": "DEVOLUCIÓN",
    "moneda": "DOLAR",
    "detalles": [
        {
            "codigoPrincipal": "1",
            "codigoAuxiliar": "1",
            "cantidad": 1,
            "descripcion": "DESCUENTO EN VOLUMEN VENTAS",
            "precioUnitario": 0.91,
            "descuento": 0,
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12.00
                }
            ]
        }
    ],
    "campoAdicional": [
        {
            "nombre": "emailCliente",
            "value": "pruebas@veronica.ec"
        }
    ]
}
```