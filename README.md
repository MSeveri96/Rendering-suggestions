# Rendering suggestions with VMD

## Draw arrows in VMD 
Copy and paste the content of the "vmd_draw_vector.tcl" in the VMD TK console and then you can draw arrows with the following command:
```

draw vector2 {a b c} {d  e f} x y

```
where a,b and c are the coordinates of the starting point of the arrow; d,e and f are the coordinates of the point that defines the arrow direction with the previous point. x is the length of the arrow and y is the resolution of the arrow. Full credit to the original tutorial, available at http://www.theochem.ruhr-uni-bochum.de/~legacy.akohlmey/cpmd-vmd/part7.html

## Reduce image "weight" from VMD

After a VMD rendering it is probable to have a very large image. To reduce its size from several MB to a few MB just open it in Inkscape and export it as png without changing the settings.


## Resize image in VMD and render it 
display resize 960 540 (for example)

the use the following keywords (plus the default ones) in Tachyon  

-aasamples 12 %s -format PNG -o %s.png  -res 1920 1080
