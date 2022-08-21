[POST: /api/v2.0/comprobantes/notas-credito](#)
```json
{
   "version":"1.0.0",
   "fechaEmision":"21/08/2022",
   "codDoc":"04",
   "ruc":"XXXXXXXXXXXXX",
   "estab":"001",
   "ptoEmi":"001",
   "secuencial":"000000001",
   "receptor":{
      "tipoIdentificacion":"04",
      "razonSocial":"Philip Torp",
      "identificacion":"9999999999999",
      "direccion":"126 Prosacco Cove"
   },
   "codDocModificado":"01",
   "numDocModificado":"001-001-000288720",
   "fechaEmisionDocSustento":"19/04/2022",
   "motivo":"DEVOLUCIÓN",
   "moneda":"DOLAR",
   "detalles":[
      {
         "codigoPrincipal":"B000Q71WNG",
         "codigoAuxiliar":"B000AOMOVE",
         "descripcion":"Hercules Double IPA",
         "cantidad":10,
         "precioUnitario":125,
         "descuento":17.86,
         "detAdicional":[
            
         ],
         "impuesto":[
            {
               "codigo":"2",
               "codigoPorcentaje":"2",
               "tarifa":12.00,
               "baseImponible":1232.14,
               "valor":147.86
            }
         ]
      }
   ],
   "campoAdicional":[
      {
         "nombre":"email",
         "value":"rolando.roc@gmail.com"
      }
   ]
}
```