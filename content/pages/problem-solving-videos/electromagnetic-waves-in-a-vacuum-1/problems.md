---
content_type: page
description: ''
draft: false
learning_resource_types: []
ocw_type: SupplementalResourceSection
parent_title: Electromagnetic Waves in a Vacuum
parent_type: SupplementalResourceSection
parent_uid: fdd03639-df5a-1302-a784-56591f1294b2
title: Problems - Electromagnetic Waves in a Vacuum
uid: 29e09e14-ee28-3ad3-56b6-668f97400ab6
---
## Electromagnetic Waves in a Vacuum

### {{< anchor "problem1" >}}{{< /anchor >}}Problem 1

Two parallel strips of metal of negligible resistance have width \\( w \\) and length \\( D \\). They are separated by a distance \\( d \\) with \\( d \\ll w \\) and \\( w \\ll D \\). At time \\( t = 0 \\) a constant potential difference, \\( V\_0 \\), is applied across the two strips at the left end of the strips and kept at \\( V\_0 \\) for all \\( t >0 \\). The system is shown in the figure below.

{{< resource uuid="a4767632-597f-7dd3-885b-40e175b53aaf" >}}

Choose some instant of time, \\( t = T>0 \\), such that the voltage across the two strips at the far end is still zero. *You may ignore the fringe fields*. At time \\( t = T \\):

1. Plot the magnitude of the electric field, \\( \\mathbf{E} \\), and magnetic field, \\( \\mathbf{B} \\) (between the strips) as a function of the longitudinal position along the strips.
2. What are the directions of the vectors \\( \\mathbf{E} \\) and \\( \\mathbf{B} \\)?
3. Compute the power supplied by the voltage source.

{{< div-with-class "reveal1">}}

› *View/Hide Hint*

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

*You can do this problem either by transmission line analysis (inductance, capacitance per unit length, etc.) or by physical reasoning on how electromagnetic fields propagate between the plates (free space).*

{{< /div-with-class >}}{{< div-with-class "reveal2">}}

› *View/Hide Answers*

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

1. \\( E\_0 = \\dfrac{V\_0}{d}, \\hspace{2mm} B\_0 = \\dfrac{E\_0}{c} \\),   plots shown below.    
      
     

{{< resource uuid="45f687ef-8b59-b78a-562c-f5201f41fdbb" >}}

1. \\( \\mathbf{E} \\) points from upper to lower strip, \\( \\mathbf{B} \\) is parallel to the strips (pointing into the paper).
2. Power supplied by voltage source = \\(\\dfrac{V\_0^2 w}{\\mu\_0 cd}\\)

{{< /div-with-class >}}

### {{< anchor "problem2" >}}{{< /anchor >}}Problem 2

Sunlight with B-field \\(\\vec{B} = 10^{-6} (B\_x, 2, 0) \\cos ( \\omega t - k\_x x + k\_y y)\\) webers/m\\(^2\\), where \\(k\_x = 8\\pi /a\\), \\(k\_y = 6\\pi/a\\) and a = 2500 nanometers, shines on a mirror-like polar ice lying in the \\(x\\)-\\(z\\) plane. The area of the ice is 100,000 square kilometers.

1. Find \\(B\_x\\), the direction, the wavelength and the frequency of the incident sunshine;
2. Find the E-field of the incident sunshine;
3. Find the Poynting vector of the incident sunshine;
4. Find the reflected E-field;{{< div-with-class "reveal3">}}

› *View/Hide Hint*    
    {{< /div-with-class >}}{{< div-with-class "toggle3">}}  
      
What are the boundary conditions at the surface of a perfect conductor?    
      
    {{< /div-with-class >}}
5. Find the total E-field;
6. Due to global warming, this piece of ice has just melted, exposing the totally absorbing black rocks underneath. How much additional energy per second is the Earth absorbing due to this melted ice? How does it compare with the average electrical power consumption of the world (about four times the US power consumption, which is the average power consumption per person times the US population)?

{{< div-with-class "reveal4">}}

› *View/Hide Answers*

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

1. The direction \\(\\hat{n} = (4/5,-3/5,0)\\); the wavelength is \\(\\lambda = a/5 = 500 \\) nm; the frequency of the incident sunshine \\(f=c/\\lambda = 6\\cdot 10^{14} \\) Hz; and \\(B\_x = 3/2\\), thus \\(\\vec{B} = 2.5\\cdot 10^{-6} (3/5,4/5,0)\\cos (\\omega t - k\_x x + k\_y y) \\) webers/m\\(^2\\).
2. The incident E-field = \\(-c \\hat{k}\\times \\vec{B} = 7.5\\times 10^2 (0,0,-1) \\cos(\\omega t - k\_x x + k\_y y)\\) Newtons/Coulomb
3. The Poynting vector of the incident light: \\begin{eqnarray} \\nonumber \\vec{S} &=& 1.5 \\times 10^3 \\cos^2(\\omega t - k\_x x +k\_y y)\\hat{n} ~\\text{Watts/m}^2 \\\\ \\nonumber \\text{\<}cos^2(\\omega t - k\_x x +k\_y y)\\text{>} &=& 0.5 \\\\ \\nonumber \\text{and so} \\hspace{22mm} \\text{\<}S\\text{>} &=& 7.5\\times 10^2 ~\\text{Watts/m}^2 \\end{eqnarray}
4. The reflected E-field = \\(7.5\\times 10^2 (0,0,1)\\cos(\\omega t -k\_x x - k\_y y)\\) Newtons/Coulomb
5. The total E-field = \\(1.5 \\times 10^3 (0,0,1) \\sin (\\omega t -k\_xx)\\sin(k\_yy)\\) Newtons/Coulomb, i.e. a propagating wave in the \\(x\\) direction and a standing wave in the \\(y\\) direction;
6. The additional energy per second absorbed by the Earth is \\begin{align\*} \\vec{S}\\cdot\\vec{A} = 4.5\\times 10^{13} ~\\text{Watts} \\end{align\*} which is much bigger than the \\(\\sim 2\\times 10^{12}\\) Watts of the average electrical power consumption of the world (\\( \\sim 10\\) billion people world-wide times 100 Watts/person, or see e.g. [Orders of magnitude (power)](https://en.wikipedia.org/wiki/Orders_of_magnitude_(power))), so global warming will accelerate faster and faster, as more and more ice melts.

{{< /div-with-class >}}

**«** {{% resource_link fdd03639-df5a-1302-a784-56591f1294b2 "Previous" %}} **|** {{% resource_link 4776ee85-e077-48e5-3b43-8907554c7d5b "Next" %}} **»**