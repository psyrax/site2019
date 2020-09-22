+++
title = "Box Scanner: Parte 1, el prototipo"
date = "2019-08-11"
author = "psyrax"
cover = "/img/box.png"
tags = ["box scanner", "proyectos"]
keywords = ["xamarin", "c&oacute;digo de barras"]
description = "Haciendo el prototipo del app para adminsitrar inventarios personales."
showFullContent = false
+++
# Intro
Hay dos proyectos que tengo pendientes desde hace mucho tiempo: hacer un app con Xamarin y hacer un app para llevar el inventario de mis cajas de cosas. Nuevo cambio :D 

## Las cajas de cosas
{{< image src="/img/cajas.png" alt="Cajas de cosas" position="left" style="border-radius: 8px; max-height:500px;" >}}

Después de un rato de no tener idea de como apilar las cosas** encontre las cajas ideales para hacerlo en home depot, valen como 30 pesos cada una y se apilan bien, por el momento tengo una configuración de columnas hechas con 6 cajas.

** Las cosas pueden ser sin estar limitadas a: controles, cables, adaptadores, mini consolas, lasers, etc.

## Xamarin
[Xamarin](https://visualstudio.microsoft.com/es/xamarin/) es un bello framework que te deja hacer apps multi plataforma usando C# (Spoiler alert, apenas y uso C#). Hay muchos tutoriales y ejemplos que me han ayudado a armar este prototipo.

## Box scanner
La idea es simple, hacer una mini app que use códigos de barras pegados en las cajas para poder adminsitrar su contenido, poder poner notas en los objetos, y tener un buscador para encontrar en la caja adecuada. Especialmente útil al momento de buscar un cable en particular o una resistencia en específico.

[Repositorio app](https://github.com/psyrax/boxScanner)

## Screenshots
Yay splash screen!
{{< image src="/img/boxScanner1.png" alt="Demo SS 1" position="left" style="margin-bottom:1em;max-height:500px;" >}}
La primera pantalla te deja elegir una caja o scanear un código de barras:
{{< image src="/img/boxScanner2.png" alt="Demo SS 2" position="left" style="margin-bottom:1em;max-height:500px;" >}}
El scanner en accion:
{{< image src="/img/boxScanner3.png" alt="Demo SS 3" position="left" style="margin-bottom:1em;max-height:500px;" >}}
Los contenidos de una caja:
{{< image src="/img/boxScanner4.png" alt="Demo SS 4" position="left" style="margin-bottom:1em;max-height:500px;" >}}
