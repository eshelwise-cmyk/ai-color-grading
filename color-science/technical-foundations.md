# Technical Foundations

## Light and capture

Camera sensors measure light and encode it into image data. The recorded signal depends on sensor characteristics, exposure, encoding, and the camera's color pipeline.

## Gamma and transfer functions

Transfer functions map scene or signal values into encoded image values. A grading workflow must know what the source encoding represents before applying corrections or transforms.

## Gamut

Gamut describes the range of colors represented by a color system. Moving between gamuts can require a defined transform or gamut-mapping strategy.

## Human vision

Perceived color depends on adaptation and surrounding colors. Evaluate grades under controlled viewing conditions when consistency matters.

## Practical rule

Know the source, working space, display transform, and delivery space before deciding which technical transform belongs in the node tree.
