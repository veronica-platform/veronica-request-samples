[POST: /api/v2.0/comprobantes/facturas](#)
Factura electrónica con más de un detalle.
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
            "cantidad": 500,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 3.90,
            "descuento": 0.00,
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12
                }
            ]
        },
        {
            "codigoPrincipal": "1000",
            "codigoAuxiliar": "0",
            "cantidad": 500,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 29.00,
            "descuento": 0.00,
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12
                }
            ]
        },
        {
            "codigoPrincipal": "1000",
            "codigoAuxiliar": "0",
            "cantidad": 1,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 120.00,
            "descuento": 0.00,
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "0",
                    "tarifa": 0.00
                }
            ]
        }
    ],
    "moneda": "DOLAR",
    "pagos": [
        {
            "formaPago": "20",
            "total": 18544,
            "plazo": "1",
            "unidadTiempo": "Días"
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