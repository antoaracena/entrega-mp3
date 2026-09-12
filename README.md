MP3 interactivo

Interfaz sonora tangible construida mediante **keyboard hack**: reemplaza una tecla convencional por un mecanismo de contacto físico creativo que, al activarse, gatilla una rutina de audio digital en tiempo real.

**Taller de Interfaces · Unidad 1: Interfaces Sonoras · Universidad Adolfo Ibáñez · 2026**
Integrantes: *(nombres del grupo, máx. 3)*

## Descripción del dispositivo
*(Reemplaza este texto por tu descripción real.)*
El dispositivo consiste en una representación de un mp3. La persona interactúa presionando un botón felpudo, lo que cierra un circuito y dispara una canción. La idea central es transformar un gesto físico cotidiano en una experiencia sonora, volviendo tangible algo que normalmente es abstracto.

## Inspiración: Museo Interactivo Mirador (MIM)
La visita al MIM fue el punto de partida. Sus exhibiciones se basan en el aprendizaje mediante la manipulación directa: el visitante entiende un fenómeno tocándolo, moviéndolo o accionándolo con su propio cuerpo, no leyéndolo.

## Cómo funciona

### Mecanismo de entrada (hardware — keyboard hack)
Se desmontó el circuito de un teclado de números y se usó su placa como interfaz de entrada al computador. El contacto se activa mediante los dos cables que se tocan al presionar el botón, que cierra el circuito correspondiente a una tecla y la envía como pulsación.

### Respuesta sonora (software — audio interactivo)
La pulsación dispara una rutina programada en **[Max/MSP · Pure Data · Web Audio API / JavaScript]**, que reproduce **[samples pregrabados / síntesis FM, aditiva o sustractiva]** 
## Diagrama técnico
El circuito del interruptor y la arquitectura del software de audio están detallados en la lámina de presentación (`lamina.png` / `lamina.pdf`).

## Estructura del repositorio
```
/
├── index.html         # página de presentación del proyecto
├── lamina.png         # lámina de presentación (o .pdf)
├── audio/             # samples / archivos de sonido
├── codigo/            # código fuente o parche (Max/Pd/JS)
├── proceso/           # fotos del proceso (desarme, soldadura, pruebas, ensamble)
└── README.md
```

## Cómo usar / ejecutar
1. Conecta el dispositivo (la placa del teclado hackeado) al computador.
2. Abre **[el parche de Max/Pd o la página web]** con la rutina de audio.
3. Activa el mecanismo de contacto: el sistema reproduce el audio en tiempo real.

## Video de demostración
mostrado en clases

