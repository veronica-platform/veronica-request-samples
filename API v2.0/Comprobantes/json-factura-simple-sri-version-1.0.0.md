[POST: /api/v2.0/comprobantes/facturas](#)
Factura electrónica con un único detalle al cual se le aplica un impuesto de 0%.
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
            "cantidad": 1,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 50.00,
            "descuento": 0.00,
            "detAdicional": [],
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
            "formaPago": "01",
            "total": 50.00,
            "plazo": "",
            "unidadTiempo": ""
        }
    ],
    "campoAdicional": [
        {
            "nombre": "Telefono",
            "value": "2784632"
        },
        {
            "nombre": "Email",
            "value": "pruebas@veronica.ec"
        }
    ]
}
 ```