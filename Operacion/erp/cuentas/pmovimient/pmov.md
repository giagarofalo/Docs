---
layout: default
title: Movimientos
permalink: /Operacion/erp/cuentas/pmovimient/pmov
editable: si
---

## Movimientos - PMOV

Las operaciones del módulo de Cuentas por Pagar en su gran mayoría se ejecutan por la aplicación movimientos, en esta aplicación donde se deben diligenciar unos datos obligatoriamente y otros que son opcionales.  

![](PMOV1.png)

**Documento:** Son los documentos que se han creado para ser utilizados en el módulo de cuentas por pagar, tan Notas Débito, Notas Crédito, Comprobantes de Egreso y Cuentas por Pagar.  
**Número:** El sistema asigna automáticamente el consecutivo de cada documento, según las especificaciones otorgadas al documento en la opción BCNS.  
**Ubicación:** Ubicación que efectúa el movimiento o al que se le aplica el movimiento, en caso de que la empresa tenga centralizado el manejo de la información.  
**Fecha:** Fecha en la cual se realiza el movimiento. Es importante puesto que es la misma fecha de la afectación contable.  
**Concepto:** Código del Concepto por el cual se hace el movimiento. Este define automáticamente la afectación contable del movimiento, por tanto debe estar perfectamente definido.  
**Motivo:** Número que identifica un documento para casos especiales a nivel contable, se puede parametrizar los documentos por conceptos en la aplicación BDOC, los motivos se parametrizan desde la aplicación BPLA.  
**Total:** Valor total del movimiento.  
**Tercero:** Código del tercero que es afectado con el presente movimiento. Todos los movimientos deben tenerlo. La cuenta contable del tercero complementa la afectación contable.  
**Nombre Tercero:** Nombre del tercero al cual afecta el movimiento.  
**Estado:** Estado del documento (Activo, Procesado y Anulado).  
**Moneda:** Campo que indica el tipo de moneda a manejar en la generación de los movimientos.  

![](PMOV2.png)

**Observación:** Observación que se desee hacer sobre el documento a registrar.  
**Cuenta:** Identificación numérica de la cuenta afectada.  
**Empleado:** Identificación numérica del empleado enacargado de generar el movimiento.  
**ClientDestinyld:** Identificación numérica del cliente a quien se destina el movimiento.  
**Negocio:** Identificación numérica del negocio.  
**Factura:** Número de la factura o documento que se está registrando.  
**Total1:** Valor total en la moneda que se realiza el movimiento.  
**Saldo:** Valor total del movimiento.  
**Impreso:** Se selecciona cuando el documento ya ha sido impreso.  

El detalle especifica las cuentas contables que se están afectando con el movimiento u operación, su naturaleza, valor, centro de costo, base de retención, etc.  

![](PMOV3.png)


**Renglón:** Consecutivo que se genera cuando se manejan varias cuentas en un comprobante.  
**Cuenta:** Identificación numérica de la cuenta.  
**Naturaleza:** Naturaleza de la cuenta (débito o crédito).  
**Valor:** Valor numérico que tiene la cuenta.  
**Tercero:** Identificación numérica del tercero.  
**Centro Costo:** Identificación del centro de costo al que pertenece la cuenta.  
**Negocio:** Identificación numérica del negocio.  
**Projectld:** Identificación numérica del proyecto.  
**BaseRetención:** Valor que se toma como base para liquidar la retención que se le aplica a un concepto.  
**Retención:** Valor de retención.  


![](PMOV4.png)

**Número:** Consecutivo del documento (PMOV) asignado.  
**Ubicación:** Ubicación organizacional que genero el documento.  
**Nombre cuenta:** Nombre de la cuenta correspondiente según PUC.  
**Nombre tercero:** Nombre del tercero al que afecta el movimiento.  
**DocDocumentld:** Documento relacionado con la cuenta por pagar.  
**DocNumberld:** Número del documento relacionado con la cuenta por pagar.  
**DocLocationld:** Ubicación del documento relacionado con la cuenta por pagar.  

![](PMOV5.png)

**Valor1:** Hace referencia al tipo de moneda origen en que se realizan determinados movimientos.  
**Fecha:** Fecha en que se realiza el movimiento.  
**Amortizado:** Número de veces que se amortizará el movimiento.  
**Documento:** Tipo de documento registrado.  






