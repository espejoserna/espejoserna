---
title: Lógica proposicional 
linktitle: Lógica proposicional 
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  logica1:
    name: Silogística
    weight: 7
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

--

![](/courses/hfc/_index_files/borde.jpg)

[Presentación en pantalla completa](https://jcunisabana.github.io/logica1/9.html#/)

## Plan

Plan
----

1.  [Los elementos del lenguaje simbólico de la lógica clásica](#/uno)
2.  [Tablas de verdad](#/dos)
3.  [Deducción natural](#/tres)

Los elementos del lenguaje simbólico de la lógica clásica
---------------------------------------------------------

Con los silogismos vimos algunas de las ventajas de un lenguaje simbólico.

Ejemplo: La validez de un silogismo BARBARA no depende de sus particularidades sino de la forma general de las proposiciones (AAA) y la figura (MP, SM, SP)

La lógica proposicional tiene como base la proposición

P
=

Q
=

R
=

S
=

En el lenguaje de la lógica proposicional, las letras que denotan proposiciones son las expresiones básicas. Para construir una expresión compuesta podemos utilizar un conectivo lógico.

Conectivos lógicos básicos
==========================

¬
-

negación

∧
-

conjunción

∨
-

disyunción

→
-

condicional

Negación
========

¬α
==

¬α
==

¬β
==

¬γ
==

¬δ
==

Conjunción
==========

∧
=

α ∧ β
=====

β ∧ β
=====

δ ∧ γ
=====

β ∧ α
=====

Disyunción
==========

∨
=

α ∨ β
=====

β ∨ β
=====

δ ∨ γ
=====

β ∨ α
=====

Condicional
===========

→
=

α → β
=====

β → β
=====

δ → γ
=====

β → α
=====

Extra
=====

Bicondicional
=============

≡
=

α ≡ β
=====

β≡ β
====

δ ≡ γ
=====

β ≡ α
=====

Fórmulas bien formadas
======================

1.  Toda letra proposicional es una fórmula bien formada.
2.  Si α es una fórmula bien formada, ¬α es una fórmula bien formada
3.  Si α y β son fórmulas bien formadas, α ∨ β es una fórmula bien formada
4.  Si α y β son fórmulas bien formadas, α ∧ β es una fórmula bien formada
5.  Si α y β son fórmulas bien formadas, α → β es una fórmula bien formada
6.  Si α y β son fórmulas bien formadas, α ≡ β es una fórmula bien formada

Tablas de verdad
----------------

Negación
========

Si P es verdadero, ¬P es falso
------------------------------

Si P es falso, ¬P es verdadero
------------------------------

| p   |     | ¬   | p   |
| --- | --- | --- | --- |
| V   |     | F   |     |
| F   |     | V   |     |

Conjunción
==========

Si α y β son ambos verdaderos,  
α ∧ β es verdadero
---------------------------------------------------

Si bien α, β o los dos son falsos,  
α ∧ β es falso
---------------------------------------------------

| p   | q   |     | p   | ∧   | q   |
| --- | --- | --- | --- | --- | --- |
| V   | V   |     | V   | V   | V   |
| V   | F   |     | V   | F   | F   |
| F   | V   |     | F   | F   | V   |
| F   | F   |     | F   | F   | F   |

Disyunción
==========

Si α y β son ambos falsos,  
α ∨ β es falso
-------------------------------------------

Si bien α, β o los dos son verdaderos,  
α ∨ β es verdadero
-----------------------------------------------------------

| p   | q   |     | p   | ∨   | q   |
| --- | --- | --- | --- | --- | --- |
| V   | V   |     | V   | V   | V   |
| V   | F   |     | V   | V   | F   |
| F   | V   |     | F   | V   | V   |
| F   | F   |     | F   | F   | F   |

Condicional
===========

Si α es verdadera y β es falsa,  
α → β es falso
------------------------------------------------

En todos los demás casos,  
α → β es verdadero
----------------------------------------------

| p   | q   |     | p   | →   | q   |
| --- | --- | --- | --- | --- | --- |
| V   | V   |     | V   | V   | V   |
| V   | F   |     | V   | F   | F   |
| F   | V   |     | F   | V   | V   |
| F   | F   |     | F   | V   | F   |

Bicondicional
=============

Si α y β tienen el mismo valor,  
α ≡ β es verdadero
----------------------------------------------------

Si α y β tienen valores diferentes,  
α ≡ β es falso
----------------------------------------------------

| p   | q   |     | p   | ≡   | q   |
| --- | --- | --- | --- | --- | --- |
| V   | V   |     | V   | V   | V   |
| V   | F   |     | V   | F   | F   |
| F   | V   |     | F   | F   | V   |
| F   | F   |     | F   | V   | F   |

Equivalencia lógica
===================

### Equivalencia lógica

Cuando dos expresiones tienen _exáctamente_ la misma tabla de la verdad, las expresiones son _lógicamente equivalentes._

### Para la próxima

* Paez, A. (2007) _Introducción a la lógica moderna_. Cap 2.

Deducción natural
-----------------

1.  Pruebas con ∧
2.  Pruebas con ∨ y → (y si queda tiempo con ≡)
3.  Pruebas con ¬ y con ⊥
4.  Pruebas con ¬ y con →
5.  Pruebas con ∨ (y si queda tiempo con ≡)

Pruebas con ∧
=============

Pruebas con  
∨ y →
===================

### (y si queda tiempo con ≡)

Pruebas con  
¬ y ⊥
===================

Pruebas con  
¬ y →
===================

Pruebas con ∨
=============

### (y si queda tiempo con ≡)