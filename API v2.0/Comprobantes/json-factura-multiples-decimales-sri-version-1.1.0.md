[POST: /api/v2.0/comprobantes/facturas](#)
Factura electrónica con soporte a más de un decimal en los campos de cantidad y precioUnitario.
```json
{
    "version": "1.1.0",
    "fechaEmision": "30/03/2021",
    "codDoc": "01",
    "ruc": "1792559480001",
    "estab": "001",
    "ptoEmi": "001",
    "secuencial": "000003519",
    "receptor": {
        "tipoIdentificacion": "04",
        "identificacion": "1711655793001",
        "razonSocial": "PRUEBAS UNITARIAS - VERONICA - RAZÓN SOCIAL",
        "direccion": "PRUEBAS UNITARIAS - VERONICA - DIRECCIÓN PRINCIPAL",
        "propina": 0
    },
    "moneda": "DOLAR",
    "detalles": [
        {
            "codigoPrincipal": "1000",
            "codigoAuxiliar": "0",
            "cantidad": 2,
            "descripcion": "CONSULTA OFTALMOLOGICA",
            "precioUnitario": 8.4821,
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
            "precioUnitario": 4.2411,
            "descuento": 0.00,
            "impuesto": [
                {
                    "codigo": "2",
                    "codigoPorcentaje": "2",
                    "tarifa": 12
                }
            ]
        }
    ],
    "pagos": [
        {
            "formaPago": "01",
            "total": 23.75,
            "plazo": "",
            "unidadTiempo": ""
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