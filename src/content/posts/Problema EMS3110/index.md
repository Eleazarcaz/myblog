---
title: Problema EMS3110 - No comunica
published: 2025-10-25
description: 'Solucion a falla tipica en computadoras EMS3110'
image: 'ems3110.jpeg'
tags: [Reparacion, guia, renault]
category: 'Reparaciones'
draft: false 
lang: 'es'
---

Un problema comun que he encontrado en estas computadoras EMS3110 que por lo general vienen en los Renault Fluence, es que deja de comunicar, se apaga, y no enciende.

La solucion que he encontrado es resoldar los pines que van clavados en la parte interna de la placa y ademas quitar la soldadura y resoldar la fuente de alimentacion.

Hay que tener paciencia para abrirlas y no dañar la carcasa, recomiendo colocar calor por alrededor de la tapa trasera, y con un desarmador plano hacer un poco de presion para levantar una esquina, eso nos permitira meter el desarmador e ir levantando lentamente la tapa.

:::tip
Usa carbuclean *disolvente* para que la silicona pierda su pegamento.
:::

Pero antes de resoldar toda la placa puedes empezar resoldando solo los pines que son de comunicacion, <font color='red'>+12v</font> y GND (tierra)

![EMS3110 - Alientech](https://www.autoelectronica.by/images/CONNECTIONS/KTAG/RENAULT/210%20EMS%203110%20IROM%20TC1766/3.png)
>EMS3110 Pinout - Alientech

Con eso deberia ser suficiente para comunicar y verificar falla.
Ahora puedes empezar a resoldar todos los pines y la fuente
![EMS3110 Resoldada](ecu1.jpeg)

Al resoldar la fuente quites la soldadura y despues apliques la nueva, puedes usar una malla desoldadora.

:::tip
Si el capacitor te molesta puedes quitarlo y cuando termines de resoldar volver a colocarlo.
:::

![capacitor](ecu2.jpeg)

El vehiculo deberia volver a funcionar.

No siempre sera la solucion, si la computadora entro en corto lo mejor seria diagnosticar que parte de la compu esta afectada.

Cualquier duda puedes mandarme un mensaje.