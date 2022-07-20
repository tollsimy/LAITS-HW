# Lens Choiche
- Mechanical, dust and water protection for the sensors.
- High FOV
- Omogenous light

## Aperture
- Aperture height 10mm -> gap between PCB and cover
- FOV = 60° (?) -> high but not to much in order to prevent incoming radiation reflected from ground.
- T = Gap + T_w (Window thickness) - S_v (Vertical sensor location relative to the package) = 10mm + 0,7mm - (=~1mm) = 9,7mm =~10mm
- Window dimension Win = 2*T*tan(90)+S_w (Sensor width)= 2*10*1.73 + 1 = 35.6mm =~ 35mm

Considering the shift of the other sensors relative to the central one (max 3mm in X and Y), a rectangular window of 38-39mm should be sufficient for all sensors.
Considering a circular window, we can determine diameter of the circumscribed circle to ~= 40mm.

## Lens
- wideband: 350-1050nm at least, considering AS7341 response.
- minimum scattering characteristic shown as AS7341 datasheet (pag. 60)
- there is no need to focus light to a specific point and, instead, there is the necessity to provide light to all light sensors (considering that using the 3 sensors version the area to be covered is about 10x10mm)

All these consideration led to a Diffuser.

Pratically, the diffuser spread the light beams in random direction.

- Thorlab BK7 diffuser, lowest price but bad characteristics. -> 12.7mm
https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=1132

- Edmund optics diffuser, perfect characteristics, high price. -> 12.5mm
https://www.edmundoptics.eu/p/125mm-dia-broadband-hybrid-diffuser/34782/

## Protective lens
https://www.fluid3dworkshop.co.uk/basket 40mm
