---
title: 'Research'
date: 2024-05-19

design:
  # Section spacing
  spacing: '2rem'

share: false
pager: false
# show_date: false
# backlinks: false

commentable: true
---

## <font size=5>Thermoacoustic Instabilities in Clean Combustion Systems</font>
### <font size=3>Introduction</font>
<font size=3>
Hydrogen, recognized as a promising alternative decarbonized fuel, has received considerable attention. However, the shift from natural gas to hydrogen in modern well-established gas turbines, which rely on lean premixed combustion to reduce NOx emissions, increases the risk of flashback, potentially causing catastrophic damage to the structure. This necessitates alternative strategies to enable safe and stable hydrogen combustion. The micro-mix concept has recently gained renewed attention for the burning of pure hydrogen. Instead of achieving a fully premixed fuel-air mixture far upstream of the flame, this strategy involves injecting fuel near the exit of the burner, allowing for rapid mixing with the incoming air flow. However, this leads to insufficient mixing and is thus often referred to as a partially premixed (or technically premixed) system since the non-uniformity of the equivalence ratio is still present at the flame. Understanding how flames respond under these conditions is critical for the development of next-generation, carbon-free gas turbines. In particular, fluctuations in the equivalence ratio -- closely linked to velocity fluctuations and strongly influenced by burner design -- play a central role in flame dynamics. Studying this coupling is therefore essential to improving the stability and safety of hydrogen combustion systems.
</font>

### <font size=3>Mode conversion: acoustic to equivalence ratio fluctuation</font>
![<font size=3>mode conversion in a partially premixed burner</font>](/uploads/Images/GenerationOfEQR.png)

<font size=3>
The generation of equivalence ratio fluctuations arises from the oscillations in the flow rate of both fuel ($m_f$) and air ($m_a$). This relation can be derived by linearizing the definition of equivalence ratio
$$
 \frac{{\phi}^\prime}{\bar{\phi}} \approx \frac{{m}_f^\prime}{\overline{{m}}_f} - \frac{{{m}}_a^\prime}{\overline{{m}}_a} \approx \frac{{u}_f^\prime}{\bar{u}_f} - \frac{{u}_a^\prime}{\bar{u}_a}
$$
where $\phi$ is the equivalence ratio just downstream of the fuel injection point, $u_f$ denotes the fuel injection velocity, and $u_a$ is the airflow velocity immediately upstream of the fuel injection. Acoustic oscillations generate velocity perturbations in the air stream, leading to corresponding variations in the air mass flow rate. If the fuel supply is not choked, pressure oscillations at the injection point can also modulate the fuel mass flow rate. These combined effects give rise to temporal fluctuations in the equivalence ratio, forming the basis of the mode conversion mechanism in partially premixed systems. 
</font>

### <font size=3>External forcing flame dynamics</font>
<font size=3>
A multi-nozzle micromix burner subjected to acoustic excitation at 1.4 kHz:
</font>
<p align="center">
{{< video src="MultiNozzle_1400Hz.mp4" controls="yes" >}}
</p>

### <font size=3>Self-excited oscillations</font>
<font size=3>
Self-excited oscillation snapshot (OH*) in a multi-nozzle micromix burner:
</font>
<p align="center">
{{< video src="MultiNozzle_SelfExcited.mp4" controls="yes" >}}
</p>
<font size=3>
Quasi-periodic oscillation:
</font>

![<font size=3>Quasi_Period_Oscillations</font>](/uploads/Images/Quasi_Period_Oscillations.png)

## <font size=5>Fundamental Research in Equivalence Ratio Fluctuations</font>
### <font size=3>Introduction</font>
<font size=3>
Both velocity and equivalence ratio fluctuations play a critical role in unsteady heat release, which can trigger thermoacoustic instability. This form of instability arises from the two-way coupling between acoustic waves and unsteady heat release, leading to large-amplitude pressure oscillations and, in severe cases, catastrophic hardware failure. However, isolated influence between velocity and equivalence ratio fluctuations on flame dynamics is difficult to distinguish, as velocity and equivalence ratio fluctuation are inherently coupled. To address this challenge, it is essential to investigate flame behavior under well-controlled equivalence ratio perturbations. Such studies not only clarify how flames respond to these fluctuations but also provide valuable insights into the nonlinear dynamics governing combustion stability.
</font>