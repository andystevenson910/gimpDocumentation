# Airbrush Tool

*Written by Samuel Bjorkman*

## Overview

The airbrush tool is a paint tool that paints with varying intensity depending on how long it is held down for. Generally speaking, it is most useful in situations that require soft transitions between colors.

## Activating the Airbrush Tool

The airbrush tool may be activated by simply pressing `A`. It can also be accessed from the toolbox by left-clicking the airbrush icon.

![toolbox with airbrush selected](../images/airbrushicon.PNG)


If the airbrush icon is not displayed in the toolbox, then a tool in the same family will be. Below are the tools in the same tool family as airbrush. One of these tools will be displayed in the toolbox; right-clicking it and then selecting `Airbrush` will activate the airbrush tool.

![tool family including airbrush](../images/airbrushtoolfamily.PNG)

## Basic Usage

Start by holding down your left mouse button, and moving your cursor to paint. Moving slower will result in thicker lines and darker shading, while moving faster will result in thinner lines and lighter shading.

Below, the image on the left shows a line drawn slowly, while the image on the right shows a similar line drawn quickly.

![line drawn slowly using the airbrush tool](../images/slowlydrawnline.PNG) ![line drawn quickly using the airbrush tool](../images/quicklydrawnline.PNG)


## Tool Options

The tool options for the airbrush tool allow you to change the functionality of the tool in useful ways. The tool options dialogue can be accessed by navigating to `Windows>Dockable Dialogues>Tool Options`. 

## Opacity

The first option in the tool options dialogue is a slider labelled `Opacity`. Adjusting it changes the maximum intensity of a stroke made with the airbrush tool. An opacity of 100 will allow you to completely cover the background you're painting over, while an opacity of 0 will produce completely invisible strokes. Anything in between will result in strokes that are partially transparent.

Below, the dot on the left was created by holding down the airbrush tool using an opacity of 100, while the dot on the right was made using an opacity of 50.

![dots drawn using the airbrush tool showing opacity](../images/airbrushopacity.PNG)

## Brushes

The second option in the tool options dialogue is labelled brushes. There will be an icon with the brush currently selected. Clicking this icon reveals all the brushes that can be used with the airbrush tool. Changing the brush will change the shape of strokes created using the tool. There are dozens of different brush presets, so you are encouraged to try for yourself which one will work best for what you're trying to do.

![airbrush brush options](../images/brushoptions.PNG)


## Size 

In the tool options dialogue, there is a slider labelled `Size`. Changing the size changes the radius of the brush you're using, measured in pixels.


## Aspect Ratio and Angle

In the tool options dialogue, there is a slider labelled `Aspect ratio`, and one below it labelled `Angle`. The aspect ratio changes the ratio of the width and height of the brush. An aspect ratio greater than 0 will result in a brush that is longer horizontally, while a ratio less than 0 will result in a brush that is longer vertically.

Below, on the left, the letter R is drawn using a brush with an aspect ratio of 1.00, while on the right, the same letter is drawn using a brush with an aspect ratio of -1.00.

![letters drawn using the airbrush tool showing aspect ratio](../images/airbrushaspectratio.PNG)


Changing `Angle` rotates the brush, allowing you to create brushes that are longer along some dimension other than up-down or left-right. The rotation amount is measured in degrees. Below, the letter R is drawn again, this time with a brush with an aspect ratio of 1.00 and an angle of 45.00.


![letter drawn using the airbrush tool showing angle](../images/airbrushangle.PNG)


## Spacing

In the tool options dialogue, there is a slider labelled `Spacing`. Strokes made by the airbrush tool are created by rapidly drawing new shapes in the same shape of the brush you're using. Spacing determines how far you have to move your cursor before the tool starts drawing a new shape, the distance being measured in pixels.

Below, the top line is drawn using a brush with spacing set to 10px. The middle line is drawn with spacing set to 50px, and the bottom line has spacing set to 100px.


![lines drawn using the airbrush tool showing spacing](../images/airbrushspacing.PNG)


## Hardness

In the tool options dialogue, there is a slider labelled `Hardness`. A hardness of 100 will result in strokes the exact same shape as the brush being used, producing strokes with hard edges. A hardness any less than 100 will feather the edges of the brush, producing strokes with softer edges.

Below, on the left, a dot is drawn using the airbrush tool with a hardness of 100. The dot on the right is drawn with a brush with a hardness of 50.

![dots drawn using the airbrush tool showing hardness](../images/airbrushhardness.PNG)


## Force

In the tool options dialogue, there is a slider labelled `Force`. Changing it will change how fast the tool will fill in strokes.

Below, the top line is drawn using a brush with force set to 20. The bottom line is drawn at about the same speed, but with force set to 100.

![lines drawn using the airbrush tool showing force](../images/airbrushforce.PNG)


## Dynamics

In the tool options dialogue, there is a section called `Dynamics`. This allows you to change functionality of the brush depending on the speed at which you paint. To the left, there is a menu with several presets for dynamics. To the right, there is text field displaying the current dynamics preset, from which you can also search for dynamics presets. Below this, there are settings for dynamics that you can manually adjust.

Below, the top line is drawn using a brush with no dynamics. The bottom line is drawn using a brush with the `Basic Dynamics` preset applied. Notice that the stroke becomes thinner at points drawn more quickly. The result is that the brush functions like a real paintbrush, which may be useful in creating certain effects.

![lines drawn using the airbrush tool showing dynamics](../images/airbrushdynamics.PNG)
