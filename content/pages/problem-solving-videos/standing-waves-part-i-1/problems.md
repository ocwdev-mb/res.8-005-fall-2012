---
content_type: page
description: ''
learning_resource_types: []
ocw_type: SupplementalResourceSection
parent_title: Standing Waves Part I
parent_type: SupplementalResourceSection
parent_uid: dd113d06-b7b5-8820-a6a4-bb05b3fc8c7e
title: Problems
uid: 698d92b2-fdd0-264b-e12d-8e48379c6a95
---
Standing Waves Part I
---------------------

### {{< anchor "problem1" >}}{{< /anchor >}}Problem 1

{{< resource f45d24c4-78f7-fef2-9d43-783daae24dbf >}}

The figure above shows a long tube filled with air. The end located at \\(x=0\\) is closed with a cap, while the opposite end, located at \\(x=L\\) is open to the atmosphere. There are two thin membranes, one located at \\(L/5 - a\\), while the other is located at \\(x= L/5 + a\\), with \\(a \\ll L\\). In between the membranes (in the shaded region) the air pressure is a constant \\(P\_0 + \\Delta\\). At time \\(t=0\\) the membranes are broken.

1.  What is the amplitude of the \\(n\\)-th normal pressure mode of this tube (without the membranes), regardless of whether or not it is excited?  
    {{< div-with-class "reveal1">}}
    
› _View/Hide Hint_
    
    {{< /div-with-class >}}{{< div-with-class "toggle1">}}
    
The boundary conditions are \\( \\dfrac{dP}{dx} = 0\\) at \\(x = 0\\) and \\(P = 0\\) at \\(x = L.\\)
    
    {{< /div-with-class >}}
2.  After the membranes are broken what is the lowest normal mode that is not excited?
3.  Now suppose the end of the tube at \\(x=0\\) has the cap removed. How would your answer for part (2) change?  
    {{< div-with-class "reveal2">}}
    
› _View/Hide Hint_
    
    {{< /div-with-class >}}{{< div-with-class "toggle2">}}
    
This part of the problem can be done without lengthy calculations.
    
    {{< /div-with-class >}}

{{< div-with-class "reveal3">}}

› _View/Hide Answers_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

1.  In this problem the overall constant \\(P\_0\\) is irrelevant, and we only need to expand the pressure difference \\(P(x, t=0)\\) in terms of the normal modes. With the tube closed at \\(x = 0\\), \\begin{equation} \\nonumber P(x,0) = \\sum\_{n=1}^{\\infty} A\_n \\cos(k\_n x) \\hspace{5mm} with \\hspace{5mm} k\_n = (n-\\frac{1}{2})\\frac{\\pi}{L} \\end{equation} and \\begin{align\*} A\_n = \\frac{4 \\Delta}{\\pi \\left(n - \\frac{1}{2}\\right)} \\left\[ \\cos\\left( \\left(n- \\frac{1}{2}\\right) \\frac{\\pi}{5} \\right) \\sin\\left( \\left(n- \\frac{1}{2}\\right) \\frac{a \\pi }{L} \\right) \\right\] \\end{align\*}
2.  The lowest normal mode that is not excited is \\(n=3\\). We can see this either through the fact that the initial conditions are symmetric about one of the nodes (it is at \\(x=L/5\\)) of the \\(n=3\\) normal mode, or by explicitly calculating \\(A\_3\\) we find it is zero.
3.  With the end cap removed the boundary conditions change such that the pressure normal modes must have a node at either end of the tube. We find that the first normal mode that has a node at \\(x=L/5\\) (and is thus the lowest unexcited mode) is \\(n=5\\).

{{< /div-with-class >}}

### {{< anchor "problem2" >}}{{< /anchor >}}Problem 2

An ideal taut string of length \\( 2L \\) is fixed at both ends. At time \\( t = 0 \\) it is stationary and distorted as shown below and is then released. The distortion can be decomposed into its Fourier components.

{{< resource 425290be-829b-0994-fa68-36029a69418c >}}

1.  Derive an expression for the amplitude of the lowest frequency component. Your answer must not contain unevaluated integrals.

    {{< div-with-class "reveal4">}}

› _View/Hide Answer_

    {{< /div-with-class >}}{{< div-with-class "toggle4">}}

The amplitude of the lowest frequency component = \\(\\left (\\dfrac{4D}{\\pi}\\right ) \\sin \\left (\\dfrac{\\pi \\Delta}{4L}\\right )\\)

    {{< /div-with-class >}}

2.  Prove that the components with the largest amplitude satisfy \\( \\lambda \\gg \\Delta \\) where \\( \\lambda \\) is the wavelength of the component, and that the amplitude of these components is approximately independent of \\( \\lambda \\).

    {{< div-with-class "reveal5">}}
    
› _View/Hide Hint_
    
    {{< /div-with-class >}}{{< div-with-class "toggle5">}}
    
You can show that for odd frequency components and \\( \\lambda \\gg \\Delta \\), the amplitude is approximately \\( \\dfrac{\\Delta D}{L} \\), which is independent of \\(\\lambda\\). By symmetry, the amplitude is zero for even frequency components.
    
    {{< /div-with-class >}}


**« {{% resource_link dd113d06-b7b5-8820-a6a4-bb05b3fc8c7e "Previous" %}} | {{% resource_link 190b5c14-4d3e-ae61-2fdd-55047c189889 "Next" %}} »**