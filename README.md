# plantillas-html
Plantillas en formato HTML para formularios de Wordpress - Libro de Reclamaciones para contact form 7

<h4>Razón Social: INVERSIONES MI EMPRESA S.A. RUC 20264000000</h4>

<label> Motivo del reclamo/queja/sugerencia
    [text* your-subject] </label>

<h3>Datos de la persona que presenta el reclamo / queja</h3>

<table>
  <tr>
    <th style="vertical-align: middle;">
<label> Seleccione el Tipo de Documento
    [select* menu-97 include_blank "DNI" "CE" "PASAPORTE" "OTRO"] </label>
</th>
    <th style="vertical-align: middle;">
<label>Número de documento
[text* text-528 placeholder "00000000"]</label>

</th>
</tr>
<tr>
    <th style="vertical-align: middle;">
<label> Nombres
    [text* your-name] </label>
 </th>
  <th style="vertical-align: middle;">
<label> Apellidos
    [text* text-392] </label>
 </th>
</tr>
<tr>
   <th style="vertical-align: middle;">
<label> Correo electrónico
    [email* your-email] </label>
</th>
    <th style="vertical-align: middle;">
<label> Número de teléfono
[text* text-393]</label>
</th>
</tr>

<tr>
   <th style="vertical-align: middle;">
<label> Dirección
[text* text-394]</label>
</th>
</tr>
<tr>
    <th style="vertical-align: middle;">
<label> Distrito
[text* text-395]</label>
</th>
 <th style="vertical-align: middle;">
<label> Provincia
[text* text-396]</label>
</th>
</tr>
</table>
<h3>Datos de la compra / comprobante / reserva del producto o servicio</h3>

<label> Seleccione si es producto o servicio
[select* menu-710 include_blank "PRODUCTO" "SERVICIO"]</label>
<label> Descripción del reclamo/queja/sugerencia
    [textarea your-message] </label>

<table>
  <tr>
   <th style="vertical-align: middle;">
<label> Número de comprobante
[text* text-397]</label>
</th>
    <th style="vertical-align: middle;">
<label> Producto o servicio en reclamo
[text* text-398]</label>
</th>
</tr>
    <th style="vertical-align: middle;">
<label> Costo del Producto o servicio en reclamo
[text* text-399]</label>
</th>
    <th style="vertical-align: middle;">
<label> Fecha de la compra
[date* date-328 min:2021-01-09 max:2030-01-01]</label>
</th>
</tr>
</table>

[acceptance acceptance-95 optional] Doy conformidad que los datos suministrados son reales y pueden ser verificados de ser necesario [/acceptance]
[acceptance acceptance-96] Acepto recibir correos a esta dirección así como las <a href="#">Políticas de Privacidad</a> [/acceptance]

[submit "Enviar Reclamo"]

Tenemos un nuevo reclamo en nuestro sitio web

<b>Datos del usuario:</b>
   Sr/Sra: [your-name] [text-392]
   Correo electrónico: [your-email]
   [menu-97]: [text-528]
   Teléfono: [text-393]

<b>Dirección:</b> [text-394],[text-395] - [text-396]
____________________________________

<b>Realiza el reclamo por el</b> [menu-710] <b>[text-398]</b> con un costo de [text-399]

Motivo del reclamo: [your-subject]

Mensaje o motivo del reclamo: [your-message]
Fecha de la compra/consumo: [date-328]
Número de comprobante: [text-397]

_____________________________________

Fecha de envío del reclamo [_date] a las [_time]
Número de reclamo grabado: 002-[text-397]22
[acceptance-95]
_____________________________________

Este mensaje se ha enviado desde un formulario de contacto en [_site_title] ([_site_url])


//* Aquí enviamos el correo al usuario *//

Sr/Sra <b>[your-name]</b>

Su reclamo por el</b> [menu-710] <b>[text-398]</b> quedó registrado con el número 002-[text-397]22

Fecha de envío del reclamo [_date] a las [_time]

[acceptance-95], esto será tomado en cuenta para los procedimientos ante Indecopi
_______________________________________

INVERSIONES TU EMPRESA S.A RUC 2046000000

Este mensaje se ha enviado desde un formulario de contacto en [_site_title] ([_site_url])
