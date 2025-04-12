---
title: Cardiac Physiology Review
author: dz  
date: 2023-11-05
categories: [Anesthesia, Cardiac]
tags: [vision loss, bone cement, ]   
mermaid: true 
math: true
---

## Cardiac and Respiratory

### Ficks Law of Diffusion

Blood to organ can be calculated using a marker substance if the amount of marker uptake per time, concentration venous and arterial of marker are known.

$$
CO = {\dot VO_2 \over Ca - Cv} = {(125ml/min) * (BSA) \over CaO_2 - CvO_2}
$$

$$
Oxygen Carrying Capacity = CaO_2 = {(Hgb * SaO_2 * 1.34) + (PaO_2 * 0.003)}
$$

### Law of Laplace

#### Arteries and AAA

The assumption is that the structure described is cylindrical. 

$$
Wall Tension (Cylinder) = {Pressure * Radius \over Wall Thickness}
$$


#### Left Ventricle and Alveoli

The assumption is that the structure described is spherical. Surfactant does help to lower the surface tension in the alveoli. 

$$
Wall Tension (Sphere) = {Pressure * Radius \over 2 *  Wall Thickness}
$$

### Poiseuille's Law for Flow or Resistance

The original law was presented for flow through a cylinder. If the equation is rearranged it represents resistance through that cylinder. Both are described below. 

#### Flow

$$
Q = {\pi r^4 \over 8L\eta }{(\Delta P)}
$$

#### Resistance

$$
R = {8L\eta \over \pi r^4 }{(\Delta P)}
$$

### Systemic Vascular Resistance SVR

$$
SVR = {MAP- CVP \over CO }{(80)}
$$

## Starling Curve!

![starling](/assets/img/starling.png)

## Subclavian Steal

![sc steal](/assets/img/scsteal.png)

## CV Specific Monitors

### CVP

![cvp](/assets/img/cvp.png)

- Loss of a Wave: 
  - A fib or V pacing without atrial contraction
- Large a Wave: 
  - Atria emptying against high resistance
  - Tricuspid stenosis, diastolic dysfx, ischemic heart, RVH, AV dissociation, junctional, V paced, PVC
- Large v Wave:
  - Tricuspid regurg

## PA Catheter

![alt text](../assets/img/pa.png)

![PA](/assets/img/pap1.png)

### When PAOP Does NOT Predict LVEDV

- Overestimates
  - Impaired LV compliance ie. ischemia
  - Mitral valve disease
  - Left to right cardiac shunt
  - Tachycardia
  - PPV
  - PEEP
  - COPD
  - Pulmonary hypertension
  - Non west zone III placement of PAC
- Underestimates
  - Aortic insufficiency

### SVO2 Interpretation
  

$$
SvO_2 = {SaO_2} - {VO_2 \over 1.38 * 10 * CO * Hgb}
$$

```mermaid
flowchart 
    
    A[SVO2] --> C[High > 80]
    A[SVO2] --> D[Low  < 60]
    A[SVO2] --> B[Normal 60-80]
    C --> E[Anesthesia, Acidosis, Toxins]
    D --> F[SaO2]
    F --> G[Normal]
    F --> H[Dec SaO2]
    H --> I[Inc FiO2 and/or PEEP]
    G --> J[Cardiac Output]
    J --> K[CI < 2]
    J --> L[CI > 2]
    K --> M[SVV or similar]
    M --> N[Low < 10]
    M --> U[High > 10]
    U --> V[Give Fluids]
    N --> O[Inotropes]
    L --> P[Hgb]
    P --> Q[Low < 8]
    Q --> R[Blood]
    P --> S[Normal > 8]
    S --> T[Analgesia vs Sedation]
```
