---
id: ecommerce-cupones-woocommerce
title: Cupones en WooCommerce
sidebar_label: Cupones en WooCommerce
---

---

_Asumiremos que ya sabes como ingresar al panel de control de WordPress y tienes acceso a tu cuenta de administrador de tienda.(Si no sabes como iniciar sesión consulta nuestro artículo sobre como [Accesar a WordPress](/docs/ecommerce-acceso-al-panel-wordpress))_

El primer paso para usar cupones con WooCommerce es activarlos, para esto **siga los siguientes pasos:**

1. Ve a: **WooCommerce** > **Ajustes** > **General**

<img alt="" src="https://conektica.com/ayuda/img/Cupones/paso-1.png" width="100%"/>

2. Desplazarse hacia abajo hasta encontrar el apartado **Activar cupones** y marcar la casilla de verificación para activar el uso de códigos de cupones.

<img alt="" src="https://conektica.com/ayuda/img/Cupones/paso-2.png" width="100%"/>

3. Desplazarse hacia abajo y guardar los cambios.

### Añadir un cupón

Ahora que los cupones se activaron es momento de agregar cupones nuevos.

**Para añadir un cupón:**

Ve a: Marketing > Cupones.

-   Una página nueva, donde no se hayan creado cupones, te mostrará una pantalla inicial que te permite crear tu primer cupón u obtener más información.

<img alt="" src="https://conektica.com/ayuda/img/Cupones/add-paso1.png" width="100%"/>

-   Una página donde ya se crearon cupones, te mostrará una pantalla que te permite crear tu primer cupón o editar los que están creados.

<img alt="" src="https://conektica.com/ayuda/img/Cupones/add-paso1.1.png" width="100%"/>

-   Crea un nuevo cupón seleccionando **Añadir cupón**. O coloca el cursor sobre uno existente para **editar**.
-   Ingresa o genera un **código de cupón**. El código es lo que será usado por el cliente para aplicar el cupón y el descuento asociado con él. Debe ser único, ya que se utiliza como identificador.
Tienes la opción de ingresar cualquier código alfanumérico que desees o de seleccionar el botón **Generar un código de cupón** si deseas que WooCommerce cree automáticamente un código de cupón aleatorio.

<img alt="" src="https://conektica.com/ayuda/img/Cupones/add-paso2.png" width="100%"/>

-   Ingresa una **Descripción** (opcional): información sobre el cupón, para uso interno. Por ejemplo: nombre de la promoción o evento, fechas vigentes, compensación, número de ticket, nombre del cliente. Esto no será visible para los clientes en la tienda.

En **Datos del cupón**, hay tres secciones que puedes usar para agregar restricciones y límites para el cupón: **General**, **Restricción de uso** y **Límites de uso**.

### General

<img alt="" src="https://conektica.com/ayuda/img/Cupones/general.png" width="100%"/>


-   **Tipo de descuento**:
    -   **Descuento en porcentaje**: un descuento porcentual solo para productos seleccionados.
    -   **Descuento fijo en el carrito**: un descuento total fijo para todo el carrito.
    -   **Descuento fijo de producto**: un descuento total fijo solo para productos seleccionados.
-   **Importe del cupón**: valor fijo o porcentaje, según el tipo de descuento que elijas. Se ingresa sin una unidad monetaria o un signo de porcentaje, los cuales se agregan automáticamente.
-   **Permitir el envío gratuito**: elimina el costo de envío cuando se utiliza el cupón. Requiere que el envío gratuito esté habilitado.
-   **Fecha de caducidad del cupón**: fecha en que el cupón debe caducar y ya no se puede usar. La caducidad ocurre a las 12:00 a.m. o a las 00:00 en la fecha elegida.

### Restricción de uso

<img alt="" src="https://conektica.com/ayuda/img/Cupones/reestriccion-de-uso.png" width="100%"/>

-   **Gasto mínimo**: te permite establecer el subtotal mínimo necesario para usar el cupón. Nota: La suma del subtotal del carrito + impuestos se utiliza para determinar la cantidad mínima.
-   **Gasto máximo**: te permite establecer el subtotal máximo permitido para usar el cupón.
-   **Uso individual**: marca la casilla si no deseas que este cupón se use en combinación con otros cupones.
-   **Excluir los artículos en oferta**: marca la casilla si no deseas que este cupón se aplique a los productos en oferta. Los cupones que sean aplicados al total del carrito no funcionarán si después se agrega un artículo en oferta.
-   **Productos**: productos a los que se aplicará el cupón o que deben estar en el carrito para que se aplique el descuento fijo o porcentual.
-   **Productos excluidos**: productos a los que no se aplicará el cupón o que no pueden estar en el carrito para que se aplique el “descuento fijo en el carrito”.
-   **Categorías del producto**: categorías de productos a las que se aplicará el cupón o que deben estar en el carrito para que se aplique el descuento fijo o porcentual.
-   **Excluir categorías**: categorías de productos a las que no se aplicará el cupón, o que no pueden estar en el carrito para que se aplique el “descuento fijo en el carrito”.
-   **Correos electrónicos permitidos**: dirección (o direcciones) de correo electrónico que pueden usar un cupón. Verificado contra el correo electrónico de facturación del cliente. También te permite incluir un carácter comodín "*" para que coincida con varias direcciones de correo electrónico, por ejemplo, *@gmail.com haría que el cupón funcione con cualquier dirección de Gmail.

**Nota: Dejar "Productos" y "Excluir productos" en blanco permite que el cupón se aplique a toda la tienda.**

### Límites de uso

<img alt="" src="https://conektica.com/ayuda/img/Cupones/limites-de-uso.png" width="100%"/>

-   **Límite de uso por cupón**: cuántas veces puede ser utilizado el cupón en total, por cualquier cliente, antes de que se convierta inválido.
-   **Limitar el uso a X artículos**: a cuántos artículos se puede aplicar el cupón antes de que se convierta inválido. Este campo solo se muestra si hay uno o más productos con los que se puede usar el cupón y es configurado en Restricción de uso.
-   **Límite de uso por usuario**: cuántas veces puede ser utilizado el cupón por un cliente, antes de que se convierta inválido para ese cliente.

Una vez que hayas configurado todos los ajustes, selecciona Publicar y ¡listo! Tu cupón estará listo para ser usado.







