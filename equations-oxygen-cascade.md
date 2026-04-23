---
layout: default
title: "Equations: Oxygen Supply Cascade and Energy Metabolism in Exercise"
---

# Oxygen Supply Cascade Equations

[← Back to home]({{ '/' | relative_url }})

A consolidated reference of the equations used across Weeks 1–4 for gas exchange, the oxygen supply cascade, and the measurement of metabolic cost and $\dot{V}O_2$. Equations are grouped by theme and listed only once, even when they appear in multiple lectures.

## Gas laws and partial pressures

| Equation | Name | Purpose |
|----------|------|---------|
| $PV = nRT$ | Ideal gas law | Relates pressure, volume, temperature, and number of moles through the universal gas constant R; the foundation for all gas behavior. |
| $P\_1 V\_1 = P\_2 V\_2$ | Boyle's law | At constant T and n, pressure is inversely proportional to volume; explains how thoracic volume change drives airflow. |
| $V\_1 / T\_1 = V\_2 / T\_2$ | Charles' law | At constant P and n, volume is directly proportional to temperature. |
| $P\_1 / T\_1 = P\_2 / T\_2$ | Gay-Lussac's law | At constant V and n, pressure is directly proportional to temperature. |
| $\frac{P\_1 V\_1}{n\_1 T\_1} = \frac{P\_2 V\_2}{n\_2 T\_2}$ | Combined gas law | General form from which the individual gas laws are derived by holding variables constant. |
| $P\_{\text{air}} = P\_{O\_2} + P\_{CO\_2} + P\_{N\_2} + \ldots$ | Dalton's law of partial pressures | Total pressure of a gas mixture equals the sum of the partial pressures of its component gases. |
| $P\_{O\_2} = P\_B \cdot F\_{O\_2}$ | Partial pressure of a gas | Partial pressure equals barometric pressure multiplied by fractional concentration. |
| $P\_IO\_2 = (P\_B - P\_{H\_2O}) \cdot F\_IO\_2$ | Inspired P<sub>O₂</sub> | Partial pressure of O<sub>2</sub> in the airways after warming and saturation with water vapor (P<sub>H₂O</sub> = 47 mmHg at 37 °C); used to start the oxygen cascade and to quantify hypoxia at altitude. |

## Pulmonary mechanics and ventilation

| Equation | Name | Purpose |
|----------|------|---------|
| $\dot{V} = \Delta P / R\_{airway}$ | Airflow equation | Rate of airflow equals the pressure difference across the airways divided by airway resistance. |
| $\dot{V}\_E = f\_b \cdot V\_T$ | Minute (expired) ventilation | Total volume of air moved in and out of the lungs per minute. |
| $\dot{V}\_A = f\_b \cdot (V\_T - V\_D)$ | Alveolar ventilation | Volume of air per minute that actually reaches the gas-exchange surfaces, after subtracting dead space. |
| $V\_{D,\text{phys}} = V\_{D,\text{anatomic}} + V\_{D,\text{alveolar}}$ | Physiological dead space | Total non-gas-exchanging ventilation volume (conducting airways plus unperfused alveoli). |

## Alveolar gas, diffusion, and respiratory exchange

| Equation | Name | Purpose |
|----------|------|---------|
| $P\_ACO\_2 = \dot{V}CO\_2 / \dot{V}\_A \cdot K$ | Clinical alveolar ventilation equation | Estimates alveolar P<sub>CO₂</sub> from CO<sub>2</sub> production and alveolar ventilation; $K = 863$ mmHg. |
| $P\_AO\_2 = P\_IO\_2 - P\_ACO\_2 / R$ | Alveolar gas equation (simplified) | Estimates alveolar P<sub>O₂</sub> from inspired P<sub>O₂</sub>, accounting for CO<sub>2</sub> dilution; explains how hyperventilation at altitude defends P<sub>A</sub>O<sub>2</sub>. |
| $R = \dot{V}CO\_2 / \dot{V}O\_2$ | Respiratory exchange ratio | Ratio of CO<sub>2</sub> output to O<sub>2</sub> uptake; reflects metabolic substrate (≈ 0.7 fat, 1.0 carbohydrate). |
| $\dot{V}O\_2 = \frac{A \cdot D \cdot \Delta P\_{O\_2}}{T}$ | Fick's law of diffusion | Rate of gas transfer is proportional to surface area and partial-pressure gradient and inversely proportional to barrier thickness. |
| $D\_LO\_2 = A \cdot D / T$ | Pulmonary diffusion capacity | Combined structural factors determining the lungs' capacity for O<sub>2</sub> transfer. |
| $\dot{V}O\_2 = D\_LO\_2 \cdot \Delta P\_{O\_2}$ | Simplified diffusion equation | O<sub>2</sub> flux across the blood–gas barrier equals diffusion capacity times the alveolar–capillary P<sub>O₂</sub> gradient. |
| $\dot{V}O\_2 = \dot{V}\_A \cdot \beta\_{gO\_2} \cdot (P\_IO\_2 - P\_EO\_2)$ | Alveolar O<sub>2</sub> delivery (capacitance form) | Ventilatory O<sub>2</sub> delivery in terms of alveolar ventilation, the capacitance coefficient for O<sub>2</sub> in air, and the inspired–expired P<sub>O₂</sub> difference. |

## Fick principle across the cascade

| Equation | Name | Purpose |
|----------|------|---------|
| $M\_x = M\_{x,\text{in}} - M\_{x,\text{out}}$ | Fick principle (general) | Conservation of mass applied to any cascade step: net uptake equals input minus output. |
| $\dot{V}O\_2 = \dot{V}\_E \cdot (F\_IO\_2 - F\_EO\_2)$ | Fick principle (ventilation, gas fractions) | Whole-body O<sub>2</sub> consumption from minute ventilation and the inspired–expired O<sub>2</sub> fraction difference; basis for indirect calorimetry. |
| $\dot{V}O\_2 = \dot{V}\_A \cdot B\_{gas} (P\_IO\_2 - P\_EO\_2)$ | Fick principle (ventilation, partial-pressure form) | Equivalent form using the capacitance coefficient of air. |
| $\dot{V}O\_2 = \dot{Q} \cdot B\_{blood} (P\_aO\_2 - P\_{\bar{v}}O\_2)$ | Fick principle (circulation, partial-pressure form) | O<sub>2</sub> uptake from cardiac output, the blood O<sub>2</sub>-carrying coefficient, and the arterio-venous P<sub>O₂</sub> difference. |
| $\dot{V}O\_2 = \dot{Q} (C\_aO\_2 - C\_{\bar{v}}O\_2)$ | Fick principle (circulation, content form) | O<sub>2</sub> uptake from cardiac output and the a–v O<sub>2</sub> content difference; the central cardiovascular form used for exercise, altitude, and diving. |
| $\dot{Q} = \dot{V}O\_2 / (C\_aO\_2 - C\_{\bar{v}}O\_2)$ | Fick principle rearranged for $\dot{Q}$ | Clinical inference of cardiac output from measured $\dot{V}O_2$ and the a–v O<sub>2</sub> content difference. |

## Cardiovascular transport

| Equation | Name | Purpose |
|----------|------|---------|
| $\dot{Q} = HR \cdot SV$ | Cardiac output | Volume of blood pumped per minute by one ventricle (L/min). |
| $SV = \dot{Q} / HR$ | Stroke volume | Volume ejected per heartbeat (L/beat); rises with training-induced cardiac hypertrophy. |
| $HR\_{\max} \approx 208 - 0.7 \cdot \text{Age}$ | Age-predicted maximum heart rate | Estimates HR<sub>max</sub> (beats/min) from age; used to prescribe exercise intensity. |

## Blood O<sub>2</sub> content and extraction

| Equation | Name | Purpose |
|----------|------|---------|
| $C\_aO\_2 = 1.39 \cdot [Hb] \cdot S\_aO\_2 + 0.003 \cdot P\_aO\_2$ | Arterial O<sub>2</sub> content | Total O<sub>2</sub> per unit blood as the sum of Hb-bound and dissolved O<sub>2</sub>. |
| $\%\text{Sat} = \frac{[O\_2]}{O\_2\,\text{capacity}} \cdot 100$ | Hemoglobin percent saturation | Fraction of Hb binding sites occupied by O<sub>2</sub>. |
| $\Delta C\_{O\_2} = C\_aO\_2 - C\_{\bar{v}}O\_2$ | a–v O<sub>2</sub> difference | Amount of O<sub>2</sub> extracted from each liter of blood passing through the tissues; widens from rest to maximal exercise. |

## Ventilation–perfusion matching

| Equation | Name | Purpose |
|----------|------|---------|
| $\dot{V} / \dot{Q} \approx 1.0$ | Ideal V/Q ratio | Optimal matching of alveolar ventilation to pulmonary perfusion; V/Q < 1 = shunt, V/Q > 1 = dead space. |

## Measurement of metabolic rate and $\dot{V}O_2$

| Equation | Name | Purpose |
|----------|------|---------|
| $\dot{V}O\_2 = \dot{V}\_E \cdot (F\_IO\_2 - F\_EO\_2)$ | Fick principle (minute ventilation and gas fractions) | Whole-body $\dot{V}O_2$ measured from minute ventilation and the inspired–expired O<sub>2</sub> fraction difference; the standard form used for indirect calorimetry. |
| $\text{Mass-specific } \dot{V}O\_2 = \dot{V}O\_2 / m\_{\text{body}}$ | Mass-specific VO<sub>2</sub> | Normalizes O<sub>2</sub> consumption to body mass (mL/kg/min) for comparisons across individuals and species. |
| $\dot{V}O\_2 = 0.1 x + 3.5$ | ACSM walking equation | Estimated $\dot{V}O_2$ (mL/kg/min) for walking at speed $x$ (m/min). |
| $\dot{V}O\_2 = 0.2 x + 3.5$ | ACSM running equation | Estimated $\dot{V}O_2$ (mL/kg/min) for running at speed $x$ (m/min). |
| $fAS = \dot{V}O\_2\text{max} / SMR$ | Factorial aerobic scope | Ratio of maximum to standard (or basal) metabolic rate; typically 5–10× in vertebrates, > 50× in flying birds. |

## Cellular energetics

| Equation | Name | Purpose |
|----------|------|---------|
| $H^+ + ADP + PCr \rightarrow ATP + \text{creatine}$ | Phosphocreatine (PCr) pathway | Fastest ATP-regeneration pathway; buffers ATP at exercise onset. |
| $C\_6H\_{12}O\_6 + 6 O\_2 \rightarrow 6 CO\_2 + 6 H\_2O + 36\,ATP$ | Aerobic metabolism of glucose | Complete oxidation of glucose in the mitochondria; actual ATP yield ≈ 29–32. |

## Whole-body O<sub>2</sub> stores (diving physiology)

| Equation | Name | Purpose |
|----------|------|---------|
| $\text{Total O}\_2 = V\_{\text{lung}} \cdot F\_{\text{lung},O\_2} + V\_{\text{blood}} \cdot C\_aO\_2 + V\_{\text{muscle}} \cdot [Mb] \cdot 1.34$ | Whole-body O<sub>2</sub> stores | Sum of O<sub>2</sub> in lung gas, blood (Hb-bound), and muscle (Mb-bound); diving specialists shift the balance toward blood and muscle. |

---

[← Back to home]({{ '/' | relative_url }}) &nbsp;|&nbsp; [Glossary of terms]({{ '/glossary-oxygen-cascade' | relative_url }})
