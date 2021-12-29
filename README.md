# Image Quilting for Texture Synthesis and Transfer

> This project implements a texture synthesis and transfer technique as described in the paper - [Image Quilting for Texture Synthesis and Transfer]

You can check out the [Project Presentation.pptx] file for more details on this project. It was made as the project for the Course - Content Based Image Retrieval (CSE3018) - Vellore Institute of Technology, Chennai

## Getting Started

Follow the instructions below to get our project running on your local machine.

1. Run `synthesis.m` file for texture synthesis and `transfer.m` file for texture transfer.
2. Replace the first line/lines with respective input image paths to generate the output images.

## Results

### Synthesis

| Input Texture                              | Output (Quilted Texture)                    | Input Texture                              | Output (Quilted Texture)                    |
| ------------------------------------------ | ------------------------------------------- | ------------------------------------------ | ------------------------------------------- |
| ![apples.png](inputs/synthesis/apples.png) | ![apples.png](outputs/synthesis/apples.png) | ![bricks.png](inputs/synthesis/bricks.png) | ![bricks.png](outputs/synthesis/bricks.png) |
| ![cans.png](inputs/synthesis/cans.png) | ![cans.png](outputs/synthesis/cans.png) | ![chocolate.png](inputs/synthesis/chocolate.png) | ![chocolate.png](outputs/synthesis/chocolate.png) |
| ![jute.png](inputs/synthesis/jute.png) | ![jute.png](outputs/synthesis/jute.png) | ![mat.png](inputs/synthesis/mat.png) | ![mat.png](outputs/synthesis/mat.png) |
| ![rice.png](inputs/synthesis/rice.png) | ![rice.png](outputs/synthesis/rice.png) | ![spots.png](inputs/synthesis/spots.png) | ![spots.png](outputs/synthesis/spots.png) |
| ![stones.png](inputs/synthesis/stones.png) | ![stones.png](outputs/synthesis/stones.png) | ![text.png](inputs/synthesis/text.png) | ![text.png](outputs/synthesis/text.png) |
| ![tomatoes.png](inputs/synthesis/tomatoes.png) | ![tomatoes.png](outputs/synthesis/tomatoes.png) | ![windows.png](inputs/synthesis/windows.png) | ![windows.png](outputs/synthesis/windows.png) |

### Transfer

| Input Texture | Input Image | Output |
| ---------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------------- |
| ![rice.png](inputs/transfer/rice.png)                                                    | ![bill.png](inputs/transfer/bill.png)                                                  | ![bill-rice.png](outputs/transfer/bill-rice.png)                                                        |
| ![fabric.png](inputs/transfer/fabric.png)                                                    | ![girl.png](inputs/transfer/girl.png)                                                  | ![girl-fabric.png](outputs/transfer/girl-fabric.png)                                                        |
| ![orange.png](inputs/transfer/orange.png)                                                    | ![potato.png](inputs/transfer/potato.png)                                                  | ![potato-orange.png](outputs/transfer/potato-orange.png)                                                        |


## Authors

* KSHITIJ KUMAR - 19BCE1170
* DEVESH GUPTA - 19BCE1579
* UTKARSH TIWARI - 19BCE1723

## Acknowledgements

- **[Prof. Geetha S.]

