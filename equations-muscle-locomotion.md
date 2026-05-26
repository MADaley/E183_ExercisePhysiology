---
layout: default
title: "Equations: Muscle Function and Energetics of Locomotion"
---

# Muscle Function and Energetics of Locomotion — Equations

[← Back to home]({{ '/' | relative_url }})

A consolidated reference of the equations used across Weeks 5–8 for muscle mechanics, musculoskeletal lever systems, the energetics of locomotion, and body-size scaling. Please see lecture notes on the units, and carefully check your work for consistency of units when solving problems.

## Muscle force, length, and velocity

| Equation | Name | Purpose |
|----------|------|---------|
| $F\_{max} = F\_{active} + F\_{passive}$ | Total isometric force | Measured force during maximally stimulated isometric contraction is the sum of active (cross-bridge) force and passive (titin + connective tissue) force. |
| $F\_{active} = F\_{max} - F\_{passive}$ | Active force | Active force is computed by subtracting separately measured passive force from the total; used to construct the active F–L curve point-by-point. |
| $(V + b)(F + a) = b(F\_0 + a)$ | Hill force–velocity equation | The classic hyperbolic relation between shortening velocity $V$ and load $F$. $F\_0$ = maximum isometric tension (at $V = 0$); $V\_0$ = maximum shortening velocity (at $F = 0$); $a$ = heat-of-shortening coefficient; $b = a(V\_0/F\_0)$. |
| $P = F \cdot V$ | Mechanical power | Instantaneous power output; computed point-by-point from the F–V curve. Peak power occurs at intermediate force and velocity (~0.2–0.3 $V\_{max}$). |
| $F\_{tot} = F\_{FV} \cdot F\_{FL} \cdot F\_{act}$ | Combined muscle model | Standard multiplicative muscle model (e.g., OpenSim): total force is the product of velocity-, length-, and activation-dependent factors. |

## Muscle architecture and scaling

| Equation | Name | Purpose |
|----------|------|---------|
| $\sigma = F / \text{PCSA}$ | Specific tension (stress) | Force normalized by physiological cross-sectional area; ~18–30 N/cm² across vertebrate skeletal muscle, used to compare intrinsic capability across muscles. |
| $F\_{max} = \text{PCSA} \times \sigma\_{spec}$ | Maximum isometric muscle force | Maximum force a muscle can produce equals its PCSA times specific tension; PCSA = muscle volume / fiber length. |
| $\text{PCSA} = \dfrac{\text{Volume}}{\text{fiber length}}$ | Physiological cross-sectional area | Cross-section of muscle perpendicular to the fibers; determines maximum force capacity (proportional to sarcomeres in parallel). |
| $F\_{max} \propto \text{PCSA}$ | Force capacity scaling | Maximum force is proportional to the number of sarcomeres in parallel — i.e., the PCSA. |
| $\text{Displacement}, V\_{max} \propto L\_{fiber}$ | Displacement and velocity capacity | Maximum shortening distance and maximum shortening velocity are proportional to the number of sarcomeres in series — i.e., the fiber length. |
| $\text{Work}, P \propto \text{Volume} = \text{PCSA} \times L\_{fiber}$ | Work and power capacity | Maximum work and power are proportional to muscle volume (or, equivalently, mass via conserved muscle density ~1.06 g/cm³). |
| $V\_{myofibril} + V\_{SR} + V\_{Mt} \approx 1$ | Cellular volume-fraction constraint | The sum of myofibrillar, SR, and mitochondrial volume fractions is constrained within a fixed muscle-cell volume; high specialization in one component comes at the expense of the others. |

## Lever systems and effective mechanical advantage

| Equation | Name | Purpose |
|----------|------|---------|
| $T = F \times D$ | Torque | Rotational effect of a force around a fulcrum, where $D$ is the perpendicular distance from the force's line of action to the fulcrum. |
| $F\_1 D\_1 = F\_2 D\_2$ | Lever balance | Torques on either side of a fulcrum balance at equilibrium. |
| $F\_{muscle} = F\_g \times \dfrac{R}{r}$ | Limb lever equation | Muscle force required to resist the ground reaction force, where $r$ is the muscle moment arm (skeletal morphology) and $R$ is the GRF moment arm (set by posture). |
| $\text{EMA} = r / R$ | Effective mechanical advantage | Ratio of muscle moment arm to GRF moment arm. Higher EMA → lower required muscle force per unit body weight; scales positively with body mass across vertebrates. |
| $T\_h = F\_g \times R\_h$ | Joint torque (inverse dynamics) | Torque at a joint from the GRF and its moment arm to that joint. |
| $W\_h = T\_h \times \Delta\theta$ | Joint work | Net work at a joint, computed by integrating joint torque through joint angular displacement. |

## Work loops and energy cycling

| Equation | Name | Purpose |
|----------|------|---------|
| $W = \oint F \, dL$ | Work loop (net mechanical work) | Net work done by a muscle equals the area enclosed by its force–length trajectory over a contraction cycle. Counterclockwise = positive (motor), clockwise = negative (brake), no enclosed area = strut/spring. |
| $L\_{\text{MTU}} = L\_{\text{CE}} + L\_{\text{SEE}}$ | Muscle-tendon unit length partition | At every instant, MTU length equals the sum of contractile-element (fascicle) length and series-elastic-element (tendon) length. |
| $F\_{\text{CE}} = F\_{\text{SEE}}$ | Series-element force balance | In a series arrangement, the contractile element and tendon transmit the same force at every instant. |
| $F\_{\text{SEE}} = k\_{\text{tendon}} \cdot \Delta L\_{\text{SEE}}$ | Tendon stiffness relationship | Tendon force is approximately proportional to tendon stretch over the operating range; stiffness $k$ increases with tendon cross-sectional area. |
| $\tau\_{exo} = k\_{rot} \times \Delta\theta\_{ank}$ | Exoskeleton torque | Passive elastic torque produced by an ankle exoskeleton, with rotational stiffness $k\_{rot}$. |

## Forces and dynamics of locomotion

| Equation | Name | Purpose |
|----------|------|---------|
| $\sum F\_{vertical} = Mg + F\_{legs} = 0$ | Vertical force balance | Average vertical force from the legs equals body weight across an integer number of strides. |
| $F\_{avg}/W\_b = T\_{step}/T\_c = L\_{step}/L\_c$ | Weyand step-cycle equation | Predicts average vertical GRF (in body weights) from the ratio of step duration to stance duration. |
| $F\_{peak} \propto 1/t\_c$ | Peak force vs. contact time | As speed rises, contact time shrinks and peak vertical GRF must rise to maintain weight support. |
| $\text{COM work} \propto s^4$ | Kuo step-length scaling | Center-of-mass work rate at step transitions scales approximately as the fourth power of step length. |

## Cost of transport and metabolic rate

| Equation | Name | Purpose |
|----------|------|---------|
| $\dot{V}O\_2 = \dot{V}\_E (F\_IO\_2 - F\_EO\_2)$ | Fick principle (respirometry) | Oxygen consumption equals ventilation rate times the difference between inspired and expired O<sub>2</sub> fractions; the basis of indirect calorimetry. |
| $\text{CoT} = \dot{V}O\_2 / \text{speed}$ | Mass-specific cost of transport | Energy used per unit distance traveled, per unit body mass (mL O<sub>2</sub> kg⁻¹ m⁻¹ or J kg⁻¹ m⁻¹). |
| $\dot{E}\_{\text{metab}}/W\_b = C \cdot (1/T\_c)$ | Kram & Taylor metabolic rate equation | Mass-specific metabolic rate per body weight equals the cost coefficient $C$ divided by stance contact time $T\_c$; $C \approx 0.189$ J/N is nearly constant across mammals. |
| $E\_{\text{cot}}/W\_b = C \cdot (1/L\_c)$ | Kram & Taylor cost-of-transport equation | CoT per body weight equals the cost coefficient $C$ divided by step length $L\_c$; larger animals have longer $L\_c$, so lower CoT. |
| $1 \text{ mL } O\_2 \approx 20.1 \text{ J}$ | Oxycaloric coefficient | Average energetic equivalent of aerobic oxygen consumption; converts respirometry data to joules. |

## Body-size scaling

| Equation | Name | Purpose |
|----------|------|---------|
| Strength $\propto L^2$, Mass $\propto L^3$ | Isometric scaling | Under geometric similarity, strength (proportional to muscle cross-section) grows with the square of linear dimension, while mass grows with the cube — larger animals are relatively weaker. |
| $\text{CoT} \propto M\_b^{-0.25}$ | CoT vs. body mass scaling | Across runners, mass-specific cost of transport decreases as body mass to the −0.25 power on log-log axes (Taylor et al. 1970). |
| $\text{fAS} = \dot{V}O\_{2max} / \text{BMR}$ | Factorial aerobic scope | Ratio of maximum to baseline metabolic rate; athletic species sit on a separate scaling line 2–4× higher than non-athletic species. |
| $\text{fAS}\_{athl} = 17.66 \cdot M\_b^{0.184}$ | Athletic-species fAS scaling | Allometric fit for athletic mammals (Weibel et al.); aerobic scope rises with body mass even within the athletic group. |
| $\text{fAS}\_{nonathl} = 8.29 \cdot M\_b^{0.100}$ | Non-athletic-species fAS scaling | Companion fit for non-athletic mammals; lower intercept and shallower slope. |

---

[← Back to home]({{ '/' | relative_url }}) &nbsp;|&nbsp; [Glossary of terms]({{ '/glossary-muscle-locomotion' | relative_url }})
