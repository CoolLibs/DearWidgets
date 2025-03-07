# DearWidgets
Collection of draw (from ImDrawList) and widgets.
Version 0.0.0.0.1

Incentivise development [Patreon](https://www.patreon.com/SoufianeKHIAT)

[<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" alt="Become a Patron" width="150"/>](https://www.patreon.com/SoufianeKHIAT)

https://www.patreon.com/SoufianeKHIAT

PR & Discussion are open.

## Features
### Draw
* Triangle Pointer {Right, Up, Left, Down}

Used internally for LineSlider

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/dearwidgetsdemo_mRxPnn8bNH.png)

* Hue Band
* Luminance Band
* Saturation Band

Used Internally to implement HueSelector.

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/dearwidgetsdemo_mw6vQsfBi7.png)
![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/dearwidgetsdemo_4ufS2JkG81.png)

* Color Ring

TODO: Ring HueSelector
TODO: Add support for 2D (angle, radius) lambda

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/GQLfC3C7Jk.gif)

* Custom Color Ring

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/Kt4ye6FDWq.gif)

* Chromatic Plot{Bilinear, Nearest}
    * Chromatic Point
    * Chromatic Line

![](https://media.githubusercontent.com/media/soufianekhiat/DearWidgetsImages/main/Images/ChromaticityPlot_puswCA4lPP.gif)

* Convex Mask

Support for ConvexMask, will fail or flip triangle if the shape is not convex. In practice some non-convex shape could work if all vertices are visible from the corner of the BoundingBox Used.

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/kYA3Dw6TmH.gif)

* DrawColorDensityPlot (aka ShaderToy)

Use carefully that can have impact on your performances for HighRes canvas or/and expensive lambda.

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/us8Fc2jkIh.png)
![](hhttps://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/yEGBSzv2F8.gif)

### Widgets
* Hue Selector

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/W0Q9VXNeGK.gif)

### Draft

Draft means draft.

#### Draw

* ChromaticityPlot

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/ChromaticityPlot_puswCA4lPP.gif)

#### Widgets

* DragLengthScalar

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/XQ3kGD9aAW.gif)

* Slider 2D Float
A version for Slider2DScaler is available for (Im{S|U}{8,16,32,64}, Float and Double)

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/0dkkSCsb5Y.gif)

* Slider 2D Int

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/PGFHy3o6Tg.gif)

* Range Select 2D

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/RangeSelect2D_EnvhshMO1B.gif)

* Slider 3D

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/IQZMEeqfx0.gif)

* Grid

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/Wj5zT2ESJu.gif)

* 2D Move

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/FoeyB7aWSp.gif)

* Line Slider (TBD)

![](https://github.com/soufianekhiat/DearWidgetsImages/raw/main/Images/4haBv2KuX7.gif)


## Constrains
C++ features used internally:
* std::string
* template
* constexpr
* if constexpr
* Lambda from template
* auto
* std::vector&lt;float&gt;, std::vector&lt;bool&gt; for isoline
