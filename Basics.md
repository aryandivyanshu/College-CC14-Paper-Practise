Pixel : Smallest unit of computer graphics, cannot be broken down further.

Resolution = width x height
            
PPI = Pixels Per Inch

Aspect ratio = Width/height 
        aspect ratio is a ratio
        Eg 4:3 . 5:2

Frame buffer : buffer=memory
    sth is tored in a buffer
    frame buffer holds graphics to be displayed 

Diplay Buffer/ refresh Memory : Stores all algo related to displaying on screen, refreshes continuously 30-60 times per second.


CRT : Cathode Ray Tube
    Strucrture : torch like diagram :
        Connector Pin -> Electron Gun -> Focusing System -> Vertical/Horizontal Deflection System -> Phospher Coated Screen  

Vector Scan(Random Scan) Display :
    Plot a specific point/line in CRT
    Plots only in a specific area
    Coordinate based plotting
    Takes help of Diplay Buffer Memory
    Display Controller controls all the display commands

Raster Scan Display:
    In vestor, we used to draw directly on specifc area, but in raster screen : we do not plot on particular point, We plot entire screen end to end on screen.
    Intensity value based
    Traverse to next pixel

ChatGPT : 
| Feature                | Random Scan                              | Raster Scan                         |
| ---------------------- | ---------------------------------------- | ----------------------------------- |
| **Display type**       | Vector display                           | Raster display                      |
| **Image formation**    | Draws lines directly using electron beam | Scans entire screen pixel by pixel  |
| **Used for**           | Line drawings, engineering graphics      | Full-color images, realistic scenes |
| **Refresh rate**       | Depends on number of lines               | Constant refresh rate               |
| **Memory requirement** | Low (stores line commands)               | High (stores pixel values)          |
| **Image quality**      | Smooth lines, no aliasing                | May show aliasing or pixelation     |
| **Animation**          | Difficult                                | Easy and flexible                   |
| **Hardware cost**      | Expensive                                | Cheaper and widely used             |
| **Resolution**         | Resolution independent                   | Resolution limited to screen pixels |
| **Examples**           | Early CRT oscilloscopes                  | Modern monitors, TVs                |



