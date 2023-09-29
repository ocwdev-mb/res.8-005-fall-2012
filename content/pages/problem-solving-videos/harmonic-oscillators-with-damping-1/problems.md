---
content_type: page
description: ''
learning_resource_types: []
ocw_type: SupplementalResourceSection
parent_title: Harmonic Oscillators with Damping
parent_type: SupplementalResourceSection
parent_uid: fe5a0c66-1af9-340e-4b31-33217f890c98
title: Problems
uid: a8b8dd22-0d73-43d0-3c09-3cc5acc938c9
---

Harmonic Oscillators with Damping
---------------------------------

### {{< anchor "problem1" >}}{{< /anchor >}}Problem 1

Using a force of 4 newtons, a damped harmonic oscillator is displaced from equilibrium by 0.2 meters. At _t_ = 0 it is released from rest. The resultant displacement of the oscillator, from the equilibrium position, as a function of time, is shown in the figure below. Estimate, as well as you can using the given information:

1.  The mass of the oscillator.
2.  The quality factor of the oscillator.

 {{< resource d8bd1536-ae1b-0e5c-1dde-8237ac8c5826 >}}

{{< div-with-class "toggle1">}}

The simplest way to do this problem is to obtain the equation of motion from conservation of energy.

{{< /div-with-class >}}{{< div-with-class "reveal2">}}

› _View/Hide Answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

Mass and _Q_ of oscillator are approximately 5 kg and 30, respectively.

{{< /div-with-class >}}

### {{< anchor "problem2" >}}{{< /anchor >}}Problem 2

{{< resource 01b66caa-2986-c6b2-5264-3f2097e0625e >}} 

The circuit shown above consists of a capacitor (\\(C\\)), an inductor (\\(L\\)) and a resistor (\\(R\\)). Initially the switch is open and the charge (\\(Q\\)) on the capacitor is \\(Q(t \\leq 0) =Q\_0\\). At \\(t = 0\\), the switch is closed.

1.  For what values of \\(R\\), the initial sign of \\(Q(t)\\) will be reversed at some later times?
2.  Assuming that the value of \\(R\\) satisfies the condition in (1), find \\(Q(t)\\) and the current \\(I(t)\\) in terms of \\(Q\_0\\), \\(R\\), \\(L\\) and \\(C\\). Draw qualitative sketches of both \\(Q(t)\\) and \\(I(t)\\). (Make sure to indicate the behaviour around \\(t=0\\)).
3.  If it takes 10 cycles for the energy in the circuit to decrease to \\(1/e\\) times its initial value, find the value of the resistance \\(R\\) in terms of \\(L\\) and \\(C\\).

{{< div-with-class "reveal4">}}

› _View/Hide Answers_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

1\.   Initial sign will be reversed only if the circuit is underdamped:

i.e., \\(R \< 2 \\sqrt{\\frac{L}{C}}\\)

2.

\\\[ Q(t) = Q\_{0} e^{-\\frac{\\gamma t}{2}} \\left(\\cos(\\omega't) + \\frac{\\gamma}{2 \\omega'} \\sin(\\omega't)\\right) \\\]        and  
\\begin{align\*}  
I(t) &= \\omega' Q\_{0} e^{-\\frac{\\gamma t}{2}} \\sin(\\omega't) + \\frac{\\gamma}{2} \\frac{Q\_{0}\\gamma}{2 \\omega'} e^{-\\frac{\\gamma t}{2}} \\sin(\\omega't)\\\\  
&= Q\_{0}\\frac{\\omega\_{0}^{2}}{\\omega'}e^{-\\frac{\\gamma t}{2}} \\sin(\\omega't).  
\\end{align\*}  
\\begin{equation}  
\\nonumber{\\text{where} \\hspace{4mm} \\gamma = {\\frac{R}{L}} \\hspace{1mm} \\text{,} \\hspace{4mm} \\omega\_{0}^{2} = {\\frac{1}{LC}} \\hspace{4mm} \\text{and} \\hspace{4mm}  
\\omega'=\\sqrt{\\omega\_{0}^{2}-\\frac{\\gamma^2}{4}}}  
\\end{equation}  
  
       Below are the sketches of \\(Q(t)\\) and \\(I(t)\\). Note that \\(I(0)=0\\) and both \\(Q(t)\\) and \\(I(t)\\) oscillate at the same frequency.

{{< resource 9812a439-44b8-d633-00f7-ad7350cd65f2 >}}

3.

\\\[R = \\dfrac{1}{20\\pi}\\sqrt{\\dfrac{L}{C}}\\\]

{{< /div-with-class >}}

**« {{% resource_link fe5a0c66-1af9-340e-4b31-33217f890c98 "Previous" %}} | {{% resource_link ccd258c9-9e21-f95c-6363-d6ee98034db2 "Next" %}} »**