[POST: /api/v2.0/comprobantes/facturas](#)
Factura electrónica con un único detalle al cual se le aplica un impuesto de 0%.

```json
{
  "version": "1.0.0",
  "codDoc": "06",
  "fechaEmision": "08/06/2023",
  "ruc": "XXXXXXXXXXXXX",
  "estab": "001",
  "ptoEmi": "001",
  "secuencial": "000000001",
  "info": {
    "dirPartida": "250 Executive Park Blvd, Suite 3400",
    "fechaIniTransporte": "08/06/2023",
    "fechaFinTransporte": "09/06/2023",
    "placa": "PXW-2600",
    "razonSocialTransportista": "María José Mera",
    "rucTransportista": "1725090235001",
    "tipoIdentificacionTransportista": "04"
  },
  "destinatario": [
    {
      "identificacionDestinatario": "1713310439001",
      "razonSocialDestinatario": "My Company (San Francisco)",
      "dirDestinatario": "250 Executive Park Blvd, Suite 3400",
      "motivoTraslado": "MOVIMIENTO INTERNO",
      "ruta": "MOVIMIENTO INTERNO",
      "detalle": [
        {
          "cantidad": 80.0,
          "codigoInterno": "E-COM07",
          "descripcion": "Gabinete grande"
        }
      ]
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
