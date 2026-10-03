# AutoClick

**Un clicador automático gratuito para Windows que hace clic por usted en el punto que elija, con el intervalo que elija, y que además puede memorizar una secuencia de puntos para pulsarlos uno tras otro.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/autoclick?lang=es)

![Pantalla de AutoClick](images/autoclick-en.webp)

## Descripción general

Hay tareas en las que hay que pulsar el mismo botón decenas o cientos de veces. AutoClick hace esos clics por usted.

Elija el botón que se pulsará (izquierdo, derecho o rueda), si se hace un clic o dos y cada cuánto tiempo, y pulse la tecla de acceso rápido (**F3** por defecto) para empezar. Pulse la misma tecla otra vez para detenerlo. La tecla funciona aunque esté mirando otro programa, así que no hace falta tener la ventana de AutoClick delante.

Si no basta con un solo punto y necesita pulsar varios por turnos, use el registro (**Grabar**). Coloque el ratón sobre un punto y pulse la tecla de acceso rápido (**F4** por defecto): esa posición se añade a la lista, una línea cada vez. Marque **Usar registro**, ejecute, y AutoClick irá pulsando los puntos en el orden de la lista.

## Funciones principales

- **Clics automáticos** — pulsa una y otra vez el botón izquierdo, el derecho o la rueda, con clic simple o doble.
- **Rango de intervalo** — haga clic con un intervalo fijo, por ejemplo cada segundo, o con un intervalo distinto cada vez entre 1 y 3 segundos. Se ajusta en centésimas de segundo.
- **Teclas globales** — inicie y detenga con una sola tecla aunque esté usando otro programa. Puede cambiarla por la combinación que prefiera.
- **Registro** — cree un patrón que pulse varias posiciones en orden, con su propio botón, tipo de clic e intervalo para cada una.
- **Guardar patrones** — guarde la lista en un archivo y ábrala cuando la necesite. La última lista vuelve tal cual la próxima vez que inicie el programa.
- **Número de repeticiones** — se detiene solo tras un número de clics fijado. Si deja el campo vacío, sigue pulsando hasta que lo detenga.
- **Mantener el cursor** — tras pulsar el punto elegido, devuelve el cursor del ratón a donde estaba.
- **Avisos** — una notificación de Windows le avisa cuando empieza y cuando se detiene. El aviso de inicio muestra también la tecla para detenerlo.
- **Modo oscuro** — sigue el modo de aplicación de Windows (claro u oscuro).
- **8 idiomas** — coreano · inglés · japonés · chino · ruso · italiano · francés · español.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/autoclick?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/autoclick?lang=es&nosetup) |

El instalador abre AutoClick en cuanto termina la instalación. Para la versión portátil, descomprima el ZIP y ejecute `AutoClick.exe`. Las dos versiones tienen las mismas funciones.

## Uso

### Primeros pasos

1. Abra AutoClick.
2. En **Configuración del Ratón**, elija el botón que se pulsará (**Ratón**), si se hace un clic o dos (**Haga clic**) y el intervalo entre clics (**Retraso**). Al principio está configurado para pulsar el botón izquierdo una vez cada segundo.
3. Coloque el cursor del ratón sobre el punto que quiere pulsar.
4. Pulse **F3**. La barra de estado inferior cambia a **Ejecutando** y AutoClick empieza a pulsar ese punto con el intervalo fijado.
5. Cuando termine, pulse **F3** otra vez. La barra de estado vuelve a **Esperando**.

### Distribución de la pantalla

| Elemento | Función |
|---|---|
| **Inicio** · **Prueba** · **Donar** | Menú superior. **Prueba** abre una página de prueba del ratón donde puede ensayar los clics |
| Logotipo de KILHO.net | Abre la página de AutoClick |
| **Configuración del Ratón** | **Ratón** (Izquierda · Derecha · Rueda) · **Haga clic** (Simple · Doble) · **Retraso** (intervalo entre clics; los dos campos forman un rango) |
| **Configuración de teclas de acceso rápido** | **Ejecutar/Detener** (F3 por defecto) · **Agregar Registro** (F4 por defecto) |
| **Otros parámetros** | **Repetir** · **Posición** (Mantener · Modificar) · **Usar avisos** (Activado · Desactivado) |
| Lista **Grabar** | Las posiciones que se pulsarán, en orden. Columnas: **Posición** · **Ratón** · **Haga clic** · **Retraso** |
| **Usar registro** | Si está marcado, al ejecutar se pulsa la lista en orden |
| **Borrar** · **Abrir** · **Guardar** | Vacía toda la lista / abre una lista guardada / guarda la lista en un archivo |
| Barra de estado | **Esperando** o **Ejecutando** |

### Qué hacer cuando…

**Pulsar siempre el mismo punto**
Coloque el cursor sobre el punto y pulse **F3**: AutoClick pulsa una y otra vez el punto donde estaba el cursor al empezar. Con **Posición** en **Mantener**, devuelve el cursor a su sitio después de cada clic, así que puede mover el ratón a otra parte mientras tanto y el punto pulsado no cambia.

**Pulsar donde esté el cursor**
Ponga **Posición** en **Modificar** y AutoClick pulsará donde esté el cursor en el momento de cada clic, no en el punto donde empezó. Es práctico si quiere ir moviendo el ratón durante la ejecución para cambiar lo que se pulsa.

**Variar un poco el intervalo cada vez**
Escriba un rango en los dos campos de **Retraso**. Por ejemplo, con `00:01.00` y `00:03.00` pulsa cada vez con un intervalo distinto entre 1 y 3 segundos. Si los dos campos son iguales, el intervalo es siempre el mismo. Los campos tienen la forma `minutos:segundos.centésimas`, así que basta con teclear los dígitos en orden para que caigan en su sitio; el valor más largo es 99 minutos 59,99 segundos.

**¿Basta con cambiar el primer campo?**
Al cambiar el primer campo y pasar a otro, el segundo se ajusta al primero. Una vez que usted edita el segundo campo, AutoClick conserva ese valor; así que, para fijar un rango, rellene primero el primer campo y después el segundo. Si el segundo es menor que el primero, se sube hasta igualar al primero.

**Pulsar un número fijo de veces y parar**
Escriba un número en **Repetir**. AutoClick se detiene solo tras ese número de clics y, si **Usar avisos** está activado, muestra el aviso «La ejecución ha finalizado al alcanzar el número de repeticiones.» mientras AutoClick parpadea en la barra de tareas. Deje el campo vacío (con **ninguno** en gris) para seguir pulsando hasta que lo detenga. Un doble clic cuenta como uno.

**Pulsar varios puntos por turnos (registro)**
1. Elija el botón, el tipo de clic y el retraso en **Configuración del Ratón**.
2. Coloque el cursor en el primer punto y pulse **F4**. Se añade a la lista **Grabar** una línea con esa posición y el botón, clic y retraso elegidos.
3. Pulse **F4** del mismo modo en cada punto siguiente. Si quiere otro botón o retraso para una línea, cambie **Configuración del Ratón** antes de pulsar **F4**.
4. Marque **Usar registro** y pulse **F3**. AutoClick pulsa desde la primera línea hacia abajo y, después de la última, vuelve a la primera. La línea que se está pulsando aparece resaltada en la lista.

El **Retraso** de cada línea es lo que AutoClick espera después de pulsar ese punto antes de pasar a la línea siguiente.

**Cambiar el orden o borrar una sola línea**
Haga clic derecho sobre una línea de la lista para ver **Subir** · **Mover Abajo** · **Eliminar**. Para vaciar toda la lista, pulse **Borrar** y luego **Sí** en la confirmación. La lista no se puede cambiar durante una ejecución, así que deténgala primero.

**Tener varios patrones y elegir uno**
Use **Guardar** para conservar la lista actual en un archivo y **Abrir** para cargarla cuando la necesite. Es cómodo tener un archivo por tarea. Aunque no guarde, la lista que tenía al cerrar AutoClick vuelve la próxima vez que lo abra. Los archivos de registro guardados con versiones anteriores se abren tal cual.

**Leer los retrasos de la lista**
Un intervalo único aparece como `00:01.00` y un rango como `01:01.00~05:03.00`, con la misma forma que los campos de entrada. Si un rango largo se ve cortado, pase el ratón por encima o arrastre el borde entre los títulos de columna para ensancharla.

**Cambiar una tecla de acceso rápido**
Haga clic en un campo de **Configuración de teclas de acceso rápido** y cambiará a «Pulse una tecla». Pulse la tecla que quiera, o una combinación con **Ctrl** · **Alt** · **Shift** (por ejemplo **Ctrl+Shift+F3**), y se cambia y guarda al instante. Pulse **Esc** en el campo para dejar esa tecla vacía (**Ninguno**). Elija una tecla que no usen los juegos u otros programas que utiliza.

**Cuando una tecla coincide con la de otro programa**
Si otro programa ya usa la misma tecla, AutoClick se lo indica. Cambie a otra tecla o cierre ese programa; una vez cerrado, al volver a abrir AutoClick su tecla original vuelve a funcionar. Si pone la misma tecla en las dos funciones, AutoClick le indica que ya se usa en otra función y no la acepta.

**Si no necesita avisos**
Ponga **Usar avisos** en **Desactivado** y AutoClick no mostrará avisos de inicio, parada ni de repeticiones completadas. Si lo deja activado, el aviso de inicio le recuerda cómo detenerlo, por ejemplo «Pulse el mismo atajo otra vez para detenerlo (F3)», algo útil si olvida la tecla.

**Pulsar el botón de la rueda**
Si elige **Rueda** en **Ratón**, se pulsa el botón de la rueda (botón central), no se desplaza la rueda. Úselo donde el botón central haga algo, como abrir un enlace en una pestaña nueva del navegador.

**Probarlo antes de empezar**
Pulse **Prueba** arriba para abrir en el navegador una página de prueba del ratón que cuenta los clics y dobles clics de los botones izquierdo, rueda y derecho. Así puede cambiar el botón, el clic y el retraso y comprobar primero que los clics salen como quiere.

**Cambiar la configuración durante una ejecución**
Durante la ejecución, los campos se bloquean para que nada cambie por accidente. Detenga con **F3**, haga los cambios y pulse **F3** de nuevo.

**Abrirlo otra vez cuando ya está abierto**
Solo se ejecuta una copia de AutoClick. Al abrirlo otra vez no se abre uno nuevo: la ventana que ya está abierta pasa al frente. El título de la ventana muestra la versión actual.

## Configuración

No hay una ventana de configuración aparte. Las teclas de acceso rápido, **Posición** y **Usar avisos** se recuerdan en cuanto los cambia, y la lista se guarda al cerrar AutoClick y vuelve la próxima vez. AutoClick sigue por su cuenta lo siguiente:

| Elemento | Sigue |
|---|---|
| Idioma | La configuración regional de Windows (inglés si el idioma no está disponible) |
| Colores | El modo de aplicación de Windows (claro u oscuro) — los cambios se aplican al instante con AutoClick abierto |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- No necesita permisos de administrador.
- No hace falta instalar ningún otro componente.
- La conexión a Internet solo se usa para los avisos de versión nueva. Todas las funciones van sin conexión.

## Actualizaciones

AutoClick **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; si pulsa **[Sí]**, abre la página de descarga y cierra el programa. Las versiones nuevas se publican manualmente tras una verificación interna y se anuncian en la [página de AutoClick](https://kilho.net/autoclick). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Licencia

AutoClick es **freeware**. Úselo gratis y sin restricciones en cualquier lugar —en el trabajo, en casa, en organismos públicos o en la escuela— y redistribúyalo libremente.

## Enlaces

- Sitio web: <https://kilho.net/autoclick>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
