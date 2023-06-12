[POST: /api/v2.0/comprobantes/notas-debito](#)

```json
{
    "version": "1.0.0",
    "codDoc": "05",
    "ruc": "XXXXXXXXXXXXX",
    "estab": "001",
    "ptoEmi": "001",
    "secuencial": "000000003",
    "fechaEmision": "12/06/2023",
    "codDocModificado": "01",
    "numDocModificado": "001-001-112312315",
    "fechaEmisionDocSustento": "01/06/2023",
    "receptor": {
        "tipoIdentificacion": "04",
        "identificacion": "1713328506001",
        "direccion": "string",
        "razonSocial": "string"
    },
    "impuesto": [
        {
            "codigo": "2",
            "codigoPorcentaje": "2",
            "tarifa": 12.0,
            "baseImponible": 50
        }
    ],
    "pagos": [
        {
            "formaPago": "17",
            "plazo": "15",
            "unidadTiempo": "string",
            "total": 56
        }
    ],
    "motivo": [
        {
            "razon": "Interés por mora",
            "valor": 50.0
        }
    ],
    "campoAdicional": [
        {
            "nombre": "email",
      "value": "soporte@veronica.ec"
        }
    ]
}
```
