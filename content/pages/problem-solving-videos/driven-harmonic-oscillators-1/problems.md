---
content_type: page
description: ''
learning_resource_types: []
ocw_type: SupplementalResourceSection
parent_title: Driven Harmonic Oscillators
parent_type: SupplementalResourceSection
parent_uid: ccd258c9-9e21-f95c-6363-d6ee98034db2
title: Problems
uid: cca16ea1-32be-6301-0b9c-8d6407cc3dc3
---

Driven Harmonic Oscillators
---------------------------

### {{< anchor "problem1" >}}{{< /anchor >}}Problem 1

A torsional oscillator comprises a cylinder with moment of inertia, \\(I\\), hanging from a light rod with torsional spring constant, \\(\\kappa\\). The cylinder also experiences a _drag torque_ equal to \\(-\\mu \\dot \\theta\\), when moving with angular velocity \\(\\dot \\theta\\). The top of the rod is driven with angular displacement \\(\\phi(t) = \\phi\_0 \\cos{\\omega t}\\).

1.  Find the _steady-state_ solution for \\(\\theta(t)\\).
2.  Plot the amplitude \\(A(\\omega) \\) and phase \\(\\delta(\\omega)\\) of your solution for \\(\\theta(t)\\) in (1) as a function of \\(\\omega\\). For your plot, assume that the natural frequency of oscillation of the system \\(\\omega\_0 = 1\\), and plot three curves on the same plot with \\(\\frac{\\mu}{I} = 0.25\\), 1 and 2. Label your curves to distinguish the three cases.

{{< div-with-class "reveal2">}}

› _View/Hide Answers_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

1.

\\begin{align\*} \\theta(t) &= \\frac{\\omega\_0^2\\,\\phi\_0}{\\sqrt{\\left(\\omega\_0^2 - \\omega^2\\right)^2 + \\gamma^2\\,\\omega^2}}\\,\\cos\\left({\\omega\\,t - \\arctan{\\left(\\frac{\\gamma\\,\\omega}{\\left(\\omega\_0^2 -\\omega^2\\right)}\\right)}}\\right) \\end{align\*} \\begin{align\*} \\text{where} \\hspace{5mm} \\gamma =\\mu/I \\hspace{5mm} \\text{and} \\hspace{5mm} \\omega\_0^2 = \\kappa/I \\end{align\*}

2.

\\begin{align\*} & A(\\omega) = \\frac{\\omega\_0^2\\,\\phi\_0}{\\sqrt{\\left(\\omega\_0^2 - \\omega^2\\right)^2 + \\gamma^2\\,\\omega^2}}\\hspace{1mm}, \\hspace{4mm} & \\tan{\\delta(\\omega)} = \\frac{\\gamma\\,\\omega}{\\left(\\omega\_0^2 -\\omega^2\\right)} \\end{align\*}

{{< resource 4076308b-0045-cd91-beed-cf11c3d53197 >}}

{{< /div-with-class >}}

### {{< anchor "problem2" >}}{{< /anchor >}}Problem 2

A capacitor (of capacitance C), a resistor (of resistance R) and an inductor (of inductance L) are connected to an AC voltage source \\(V = V\_0 \\sin(\\omega t)\\) starting at \\(t=0\\) as shown in the diagram below.

{{< resource de02249c-029d-ec40-be2a-38aa808769b0 >}}

Assuming that both the current and the charge of the capacitor are initially zero, determine the expression for \\(V\_C(t\\ge0)\\) with \\(\\omega=\\omega\_0=\\dfrac{1}{\\sqrt{LC}}\\) and \\(L \< 4R^2C\\).

{{< div-with-class "reveal4">}}

› _View/Hide Answer_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}\\begin{align\*} V\_C(t\\ge0) = V\_{0}\[-\\dfrac{\\omega\_{0}}{\\omega'}e^{-\\frac{\\gamma t}{2}} \\sin(\\omega't) + \\sin(\\omega\_{0}t)\] \\end{align\*} \\begin{align\*} \\text{where} \\hspace{5mm} \\omega' = \\sqrt{\\frac{1}{LC} - \\frac{1}{4R^2C^2}} \\hspace{5mm} \\text{and} \\hspace{5mm} \\gamma = \\frac{1}{RC} \\end{align\*}

{{< /div-with-class >}}

**« {{% resource_link ccd258c9-9e21-f95c-6363-d6ee98034db2 "Previous" %}} | {{% resource_link aa292064-0a88-b394-2f27-c6d5da58e597 "Next" %}} »**