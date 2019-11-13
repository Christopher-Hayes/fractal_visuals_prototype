# Fractal Visuals Prototype
This is a HTML/CSS + BabylonJS prototype for the 3d fractal visuals that are rendered with the LibIGL (OpenGL) application in the [MFM](https://github.com/christopher-hayes/fracmap) and [FracMAP](https://github.com/christopher-hayes/fracmap) (MFM is the successor). These simple, single page applications were built to quickly test the data from the fractal generator in a qualitative manner. These apps will not show the most quality code (data was even pasted into the Javascript), but they did their job to verify results as quickly as possible. The final product uses LibIGL (OpenGL) with NanoGUI to provide 3d visuals of the generated fractal.

### variable_k.html

This page shows multiple runs of the fractal code with different k values. The k value represents the monomer overlap, 0.5 would be total overlap and 1.0 would be no overlap.

![Screenshot of the 3D Fractal model showing overlap from the k variable](https://github.com/Christopher-Hayes/fractal_visuals_prototype/raw/master/screenshot_variable_k.png)

### variable_n.html

This page shows multiple runs of the fractal code with different n values. The n value represents the total number of monomers generated.

![Screenshot of the 3D Fractal model showing a certain number of monomers as influenced by the n variable](https://github.com/Christopher-Hayes/fractal_visuals_prototype/raw/master/screenshot_variable_n.png)
