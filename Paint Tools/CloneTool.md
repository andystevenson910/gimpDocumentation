# Using the Clone Tool in GIMP

*Written by Andrew Stevenson*

## 1. Open GIMP and Your Image:

- Launch GIMP on your computer.
- Go to `File` > `Open` and select the image you want to work on.

## 2. Select the Clone Tool:

- Click on the ![CloneTool.png](../images/CloneTool.png) *Clone Tool*.
- Alternatively, you can press the shortcut key `C` to activate the ![CloneTool.png](../images/CloneTool.png) *Clone Tool*.
![Selecting Clone Tool](../images/CloneToolSelection.png)

## 3. Adjust the Tool Settings:

In the Tool Options pane below the main toolbox, you can adjust various settings for the ![CloneTool.png](../images/CloneTool.png) *Clone Tool*:
- **Size:** Adjusts the diameter of the brush.
- **Hardness:** Adjusts the edge softness of the brush.
- **Opacity:** Adjusts the transparency of the cloned area.

![Size Hardness and Opacity are Highlighted](../images/CloneToolAdjustments.png)


## 4. Set the Clone Source:

- Move the cursor to the area of the image you want to use as a source for cloning.
- Hold down the `Ctrl` key and click once. Note that the cursor changes shape,indicating you are in source mode.
- This sets the source point for cloning.

## 5. Start Cloning:

- Move the cursor to the area where you want to apply the clone.
- Press and hold the left mouse button and start painting over the area you want to cover. As you paint, you'll notice that the source point also moves, indicating which part of the image it's 
sampling from.

## 8. Finalize and Save:

- Once you're satisfied with the cloning, you can further adjust, edit, or enhance your image using other tools and filters in GIMP.
- To save your edited image, go to `File` > `Export As` and choose your preferred file format and settings.

# Other Settings:

## Alignment Mode:

### None Mode
Clones from the initial source point for each new brushstroke, with no relation to previous strokes.

### Aligned Mode
Maintains a consistent offset between source and destination across all brushstrokes after the first.

### Registered Mode
Clones from a source layer to a target layer, aligning each cloned pixel to its corresponding location in the source.

### Fixed Mode
Clones from a fixed source origin, repeating the same sample with each brushstroke regardless of brush movement.

![Selecting Alignfment Mode](../images/FRANModes.png)

# Tips:
- Zoom in for more precision while cloning.
- Regularly change the source point to avoid repetitive patterns.
- For large areas, use a bigger brush size, but for detailed work, switch to a smaller brush.

