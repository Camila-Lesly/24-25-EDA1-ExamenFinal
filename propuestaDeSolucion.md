# 24-25-EDA1-ExamenFinal - Propuesta de solución

<div align=center>

|||
|-|-|
|![](/images/IMG_20250123_115901.jpg)|![](/images/modelosUML/001.svg)

</div>

## Código implementado

<div align=center>

|Clases|
|-|
[Demo](/src/Demo.java)
[GestorPantalla](/src/GestorPantalla.java)
[PantallaEntrelazada](/src/PantallaEntrelazada.java)
[ListaCircularFrames](/src/ListaCircularFrames.java)
[Frame](/src/Frame.java)
[Pixel](/src/Pixel.java)
[Coordenada](/src/Coordenada.java)

</div>

### Ejecución

Demo asumiendo una pantalla de 8x3 (o sea, dos frames de 4x3 cada uno)

<div align=center>

<table>
<tr>
<td valign=top>

```java
GestorPantalla pantalla = new GestorPantalla(8,3);

pantalla.establecerPixel(new Coordenada(7,2),2);
pantalla.establecerPixel(new Coordenada(6,1),2);
pantalla.establecerPixel(new Coordenada(5,0),2);
pantalla.renderizar();
```
</td>
<td valign=top>

```
00000200
00000020
00000002
```
</td>
</tr>
</table>

</div>