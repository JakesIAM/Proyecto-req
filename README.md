# Proyecto-req

Aquí tienes un ejemplo técnico, listo para pegar en un archivo .md compatible con Mermaid (como Obsidian, Notion, o un viewer online):

```mermaid
flowchart TD
    A[Inicio] --> B[Ingesta de alcohol<PE>(ml de bebida y % alcohol)]
    B --> C[Calcular gramos de alcohol puro<br>Gramos = Volumen (ml) x Graduación (%) x 0.8]
    C --> D[Seleccionar sexo de la persona]
    D --> E{Sexo}
    E -->|Hombre| F[Coeficiente de Widmark: 0.68]
    E -->|Mujer| G[Coeficiente de Widmark: 0.55]
    
    F --> H[Peso corporal en kg]
    G --> H

    H --> I[Calcular BAC inicial:<br>BAC = (Gramos de alcohol) / (Peso × Coeficiente) × 100]
    I --> J[Horas desde la última bebida]
    J --> K[Reducción por metabolismo:<br>0.015 × horas]
    K --> L[Calcular BAC final:<br>BAC_final = BAC_inicial - reducción]

    L --> M{Resultado BAC}
    M -->|BAC < 0.03%| N[Bajo o sin efecto significativo]
    M -->|0.03% ≤ BAC < 0.08%| O[Capacidad reducida (legal en muchos países)]
    M -->|BAC ≥ 0.08%| P[Ilegal para conducir en muchos países]
```

📌 ¿Qué muestra el diagrama?

Este flujo representa el proceso típico para calcular el nivel de alcohol en sangre usando la fórmula de Widmark:

BAC
=
𝐴
𝑟
⋅
𝑃
×
100
−
𝛽
⋅
ℎ
BAC=
r⋅P
A
	​

×100−β⋅h

Donde:

A: gramos de alcohol consumido

r: coeficiente de difusión (0.68 hombre, 0.55 mujer)

P: peso en kg

β (beta): tasa de eliminación (~0.015% por hora)

h: horas desde la última bebida


Botones de interacción (si vas a implementarlo en una web)

¿Quieres que lo exporte como PDF o HTML también?
