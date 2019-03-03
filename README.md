# rtv1

## Scene file exemple :<br/>
    // Comment lines begin with "// ";
    CAM {position: (0, 0, -2000), direction: (0, 0, 1)};
    MAT {diffusion: (255, 255, 0), reflexion: 0, specvalue: 100, specpower: 50};
    LIGHT {position: (640, 240, -10000), intensity: (255, 255, 255)};
    SPHERE {center: (233, 290, 0), radius: 100, mat: 0};
    CYLINDER {direction: (1, 0, 1), axispoint: (500, 600, 0), radius: 100, mat: 1};
    CONE {direction: (0, 1, 0), center: (500, 300, 200), angle: 15, mat: 0};<br/>

<br/>
Positions like 'position', 'center' and 'axispoint' are (x,y,z) absolute coordinates.<br/>
Radius is also an absolute value.<br/>
Vector and direction are (x,y,z) normalize values.<br/>
Intensity and diffusion are the R,G,B components of the color between 0 and 255.<br/>
Specvalue and specpower are for brightness between 0 and 100.<br/>
The mat is the number of the material from the previous declaration.<br/>
The angle is in degree.<br/>