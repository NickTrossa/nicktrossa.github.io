---
layout: post
title: Desde la Ley de Faraday Lenz hasta el modelo de transformador
subtitle: Notas de una clase de Laboratorio de electricidad
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [física, inducción]
comments: true
mathjax: true
author: Nicolas  Torasso
---
# ¿Qué es un transformador?
Un transformador es un aparato eléctrico que funciona solo con corriente alterna y tiene dos utilidades fundamentales:
- Desacoplar el potencial de referencia de dos circuitos (también conocido como obtener un circuito "flotante").
- Aumentar o reducir la tensión de un circuito. Es decir, como cuando conectábamos la vieja Play Station 1 que alguien trajo del exterior, nos permitía obtener 110 V a partir de 220 V.

Primero mostraremos el origen de la impedancia de un inductor L: $$Z_L = i ω L$$:
# La Ley de Faraday-Lenz y las espiras
Si por un conductor (i.e., un cable) que forma una espira hacemos circular una corriente, entonces esta generará un campo magnético alrededor del cable siguiendo la [Ley de Ampère](https://es.wikipedia.org/wiki/Ley_de_Amp%C3%A8re). Si esa corriente es alterna, entonces el campo magnético también lo será, y por lo tanto el flujo de campo magnético en la espira tendrá una dependencia temporal. La **Ley de Faraday-Lenz** establece que ante cualquier variación de flujo magnético a través una superficie (puede ser cualquiera, pero en nuestro caso nos sirve pensar en aquella formada por la espira) se inducirá una fuerza electromotriz ε dada por\
$$\varepsilon = \frac{d \Phi}{d t}$$\
donde\
$$\Phi = \int_S{\vec{B}.d\vec{S}}$$

Detengámonos aquí un segundo para responder lo siguiente:
1. ¿Qué significa que exista una fuerza electromotriz ε en mi circuito? --> Simplemente que si hay portadores de cargas, sentirán la acción de esta fem, que actúa de la misma forma que una diferencia de potencial. La diferencia de potencial estára dada a lo largo del borde de la superficie en cuestión que determina el flujo (A y B en la Figura).
3. ¿Y cómo calculamos el campo $$\vec{B}$$?\ --> Pues, usando la Ley de Biot-Savart:\
   $$\vec{B} = \int{\frac{{\mu _0 }}{{4\pi }}\frac{{I \vec{d\ell} \times {(\vec{r}-\vec{r'})}}}{{|\vec{r}-\vec{r'}|^3 }}}$$
   


