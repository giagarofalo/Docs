---
layout: default
title: Pedidos
permalink: /Operacion/scm/ventas/vpedido/vped
editable: si
---

# VPED - Pedidos

Esta es la pantalla maestra que sirve para adicionar, consultar y modificar los pedidos que hacen los clientes a la empresa. Esta pantalla es fundamental para la captura de las órdenes de compra de los clientes ya que se encuentra integrada a los módulos de cartera e inventarios, con cartera en la validación del cupo y condiciones comerciales y con inventarios en la disponibilidad de los productos.  


![](vped1.png)

**Documento:** PD de pedido.  
**Número:** consecutivo generado automáticamente.  
**Ubicación:** Número de ubicación de la empresa la cual realiza el documento.  
**Concepto:** PD de pedido.  
**Motivo:** Motivo parametrizado previamente en la aplicación **BMOT**.  
**Fecha:** Fecha en que se registra el pedido.  
**Tercero:** Número de identificación del tercero que solicita el pedido.  
**Nombre Tercero:** Nombre del tercero que solicita el pedido.  


![](vped2.png)

**Moneda:** Doble clic y seleccionar tipo de moneda utilizada para el pedido.  
**Estado:** Estado del pedido: Activo, Procesado, Anulado.  
**Vendedor:** Número de cédula del vendedor.  
**TipoPrecio:** Doble clic y seleccionar si es Normal y Minoristas.  
**% Descuento:** Número del porcentaje de descuento a realizar.  
**Ordencompra:** Número de la orden de compra.  
**Condición Pago:** Doble clic y seleccionar la condición de pago acordada.  

![](vped3.png)

**Bruto:** Valor bruto del pedido.  
**Descuento:** Valor en cifras del descuento acordado.  
**Subtotal:** Resta del valor bruto menos el descuento acordado.  
**TaxSale:** Valor de impuestos.  
**Total:** Suma del subtotal más el valor de los impuestos.  
**Impreso:** Se marca cuando se ha impreso el documento.  
**DeliveryDateMax:** Fecha de entrega máxima.  

![](vped4.png)

**Crédito:** Estado del crédito.  
**Comercial:** Estado de aprobación por comercial.  
**Liberación:** Si se liberó o no.  
**LiberationCommercial:** Si la liberación se realizó por comercial.  
**Consignación:** Si se realizó la consignación o no.  
**ProjectId:** Identificación del proyecto al que pertenece.  
**Observación:** Comentarios.  

Esta aplicación consta de una ventana en la parte inferior llamada detalle:

![](vped5.png)

**Renglón:** Número del renglón del detalle a registrar.  
**Producto:** doble clic y seleccionar número del producto.  
**Nombre Producto:** Nombre del producto arrojado automáticamente.  
**Cantidad:** Cantidad del producto del pedido.  
**Precio:** Precio del producto.  
**%Imp:** Número del porcentaje de impuesto.  
**%Descuento:** Número del porcentaje de descuento del pedido.  

![](vped6.png)

**Total:** Valor total del pedido.  
**Bodega:** Bodega de donde proviene el producto.  
**Fecha Entrega:** Fecha de entrega del pedido.  

## [Consultas dinámicas](http://docs.oasiscom.com/Operacion/scm/ventas/vpedido/vped#consultas-dinámicas)

Realización de una consulta dinámica en la aplicación _VPED - Pedidos_.  

![](vped7.png)

## [Verificación de Pedidos](http://docs.oasiscom.com/Operacion/scm/ventas/vpedido/vped#verificación-de-pedidos)

Realizado el pedido en la aplicación [**Comprar**](http://docs.oasiscom.com/Operacion/marketplace/comprar), ingresaremos a la aplicación _VPED - Pedidos_ y filtraremos por la fecha en la que se realizó nuestro pedido. Si los productos y/o servicios seleccionados corresponden a diferentes proveedores, se generarán dos transacciones diferentes en VPED.  

En el ejemplo del pedido realizado en la aplicación [**Comprar**](http://docs.oasiscom.com/Operacion/marketplace/comprar), seleccionados una jarra y una maleta, estos dos artículos son de proveedores diferentes, por lo tanto se verán los pedidos en dos documentos diferentes como se muestra a continuación.  

Pedido de la Jarra

![](vped8.png)

Pedido de la Maleta

![](vped9.png)


