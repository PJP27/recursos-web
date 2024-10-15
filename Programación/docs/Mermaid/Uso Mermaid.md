<style>
  
.md-header__button.md-logo img{
            fill: currentcolor;
            display: block;
            height: 3rem;
            width: auto;
        }
.center {
    display: flex;
    flex-direction:column;
    align-items:center;
}
</style>
        
# 1. Diagramas de flujo

Un diagrama de flujo es un tipo de diagrama que representa un algoritmo, flujo de trabajo o proceso. El diagrama de flujo muestra los pasos como casillas de diversos tipos, y su orden conectando las casillas con flechas. Esta representación diagramática ilustra un modelo de solución a un problema dado.

## 1.1 Gráfico

Las direcciones posibles son:

* TB - arriba abajo
* BT - abajo arriba
* RL - derecha izquierda
* LR - izquierda derecha
* TD - igual que TB

<div class="center">
<table>
  <thead>
    <tr>
      <th>Direction</th>
      <th>Diagram</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB</td>
      <td>
        <div class="mermaid">

``` mermaid
    graph TB;
    A-->B;
```

        </div>
      </td>
      <td><code>graph TB; A-->B;</code></td>
    </tr>
    <tr>
      <td>BT</td>
      <td>
        <div class="mermaid">

```mermaid
    graph BT;
    A-->B;
```

        </div>
      </td>
      <td><code>graph BT; A-->B;</code></td>
    </tr>
    <tr>
      <td>RL</td>
      <td>
        <div class="mermaid">

```mermaid
    graph RL;
    A-->B;
```

        </div>
      </td>
      <td><code>graph RL; A-->B;</code></td>
    </tr>
    <tr>
      <td>LR</td>
      <td>
        <div class="mermaid">

```mermaid
    graph LR;
    A-->B;
```

        </div>
      </td>
      <td><code>graph LR; A-->B;</code></td>
    </tr>
    <tr>
      <td>TD</td>
      <td>
        <div class="mermaid">

```mermaid
    graph TD;
    A-->B;
```

        </div>
      </td>
      <td><code>graph TD; A-->B;</code></td>
    </tr>
  </tbody>
</table>
</div>
## 1.2 Nodos y formas
<div class="center">
<table>
  <thead>
    <tr>
      <th>Característica</th>
      <th>Diagrama</th>
      <th>Definición</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nodo (Predeterminado)</td>
      <td>
        <div class="mermaid">

```mermaid
    graph LR;
    id;
```

    </div>
  </td>
  <td><code>graph LR; id;</code></td>
</tr>
<tr>
  <td>Nodo con Texto</td>
  <td>
    <div class="mermaid">

```mermaid
    graph LR;
    id1[Este es el texto en la caja]
```
    </div>
  </td>
  <td><code>graph LR; id1[Este es el texto en la caja]</code></td>
</tr>
<tr>
  <td>Nodo con Bordes Redondeados</td>
  <td>
    <div class="mermaid">
```mermaid
    graph LR;
    id1(Este es el texto en la caja)
```
    </div>
  </td>
  <td><code>graph LR; id1(Este es el texto en la caja)</code></td>
</tr>
<tr>
  <td>Nodo en Forma de Círculo</td>
  <td>
    <div class="mermaid">
```mermaid
    graph LR;
    id1((Este es el texto en el círculo))

```

    </div>
  </td>
  <td><code>graph LR; id1((Este es el texto en el círculo))</code></td>
</tr>
<tr>
  <td>Nodo en Forma Asimétrica</td>
  <td>
    <div class="mermaid">
``` mermaid
    graph LR;
    id1>Este es el texto en la caja]

```
    </div>
  </td>
  <td><code>graph LR; id1>Este es el texto en la caja]</code></td>
</tr>
<tr>
  <td>Nodo en Forma de Rombo</td>
  <td>
    <div class="mermaid">
```mermaid
    graph LR;
    id1{Este es el texto en la caja}
```
    </div>
  </td>
  <td><code>graph LR; id1{Este es el texto en la caja}</code></td>
</tr>
</tbody> </table>
</div>
## 1.3 Enlaces entre nodos
<div class="center">
<table>
  <thead>
    <tr>
      <th>Característica</th>
      <th>Diagrama</th>
      <th>Definición</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Enlace con Punta de Flecha</td>
      <td>
        <div class="mermaid">

```mermaid
    graph LR;
    A-->B
```

    </div>
  </td>
  <td><code>graph LR; A-->B</code></td>
</tr>
<tr>
  <td>Enlace con Punta de Flecha y Texto (1)</td>
  <td>
    <div class="mermaid">

```mermaid
    graph LR;
    A-->|texto|B

```
    </div>
  </td>
  <td><code>graph LR; A-->|texto|B</code></td>
</tr>
<tr>
  <td>Enlace con Punta de Flecha y Texto (2)</td>
  <td>
    <div class="mermaid">
```mermaid
    graph LR;
    A-- texto -->B

```
    </div>
  </td>
  <td><code>graph LR; A-- texto -->B</code></td>
</tr>
<tr>
  <td>Enlace Punteado</td>
  <td>
    <div class="mermaid">
```mermaid
    graph LR;
    A-.->B;

```

    </div>
  </td>
  <td><code>graph LR; A-.->B;</code></td>
</tr>
<tr>
  <td>Enlace Punteado con Texto</td>
  <td>
    <div class="mermaid">

```mermaid
    graph LR;
    A-. texto .-> B

```
    </div>
  </td>
  <td><code>graph LR; A-. texto .-> B</code></td>
</tr>

</tbody> </table>

</div>