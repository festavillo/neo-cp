---


---

<h1 id="neo-compresion-neo-cp">NEO Compresion (NEO-CP)</h1>
<dl>
<dt>NEO</dt>
<dd>Notificacion de Eventos Operativos</dd>
</dl>
<h2 id="descripcion-de-fases-del-proyecto">Descripcion de fases del proyecto</h2>
<ul>
<li>
<h3 id="fase-1---carga-neo-cp-en-rosario-cog-neo-cp">Fase 1 - Carga NEO-CP en Rosario (COG-NEO-CP)</h3><ul>
<li>
	* Carga de parametros comunes a todos los clientes</li>
<li>Niveles de Carga y Control: Operador  -&gt;  Supervisor  -&gt;> COG.</li>
<li>
	* Reportes periodicos basicos</li>
</ul>
</li>
<li>
<h3 id="fase-2----carga-neo-cp-en-plantas-compresoras-hmi-neo-cp">Fase 2  - Carga NEO-CP en Plantas Compresoras (HMI-NEO-CP)</h3>
<ul>
<li>Carga de los partes diarios en el servidor de Telemetria local de cada Planta Compresora</li>
<li>Incorporacion de parametros propios de cada Cliente/Contrato</li>
<li>Sincronizacion periodica con COG-NEO-CP (NEO Rosario)</li>
</ul>
</li>
<li>
<h3 id="fase-3---integracion-telemetria-de-planta-compresora-cog-neo-cp">Fase 3 - Integracion Telemetria de Planta Compresora (COG-NEO-CP)</h3>
<ul>
<li>Integracion de principales variables con lectura automatica</li>
<li>Reglas de validacion de datos manuales y automaticos</li>
<li>Reportes de causas de carga manual</li>
</ul>
</li>
</ul>
<h2 id="cronograma-preliminar-de-ejecucion-del-pr

## Cronograma preliminar de ejecucion del proyecto

```mermaid
gantt
    title NEO Compresion
    dateFormat  YYYY-MM-DD
    section Fase 1
    Analisis           :a1, 2020-05-26, 20d
    Desarrollo         :a2, after a1, 30d
    Implementacion piloto (5 Plantas)     :a3, after a2  , 20d
    Implementacion completa     :a4, after a3  , 30d

    section Fase 2
    Analisis           :a5, after a4 , 20d
    Desarrollo         :a6, after a5, 20d
    Implementacion piloto (5 Plantas)     :a7, after a6  , 10d
    Implementacion completa     :a8, after a7  , 30d

section Fase 3
    Analisis           :a9, after a8 , 10d
    Desarrollo         :a10, after a9, 30d
    Implementacion piloto (5 Plantas)     :a11, after a10  , 10d
    Implementacion completa     :a12, after a11  , 20d

```

# Lenguajes de programacion y Herramientas de desarrollo previstas

## Back-end

### - Laravel
### - PHP

## Front-end

### Laravel



<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA2NzIzMDAxOF19
-->