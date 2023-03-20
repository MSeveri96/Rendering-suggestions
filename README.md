# Rendering-suggestions

## Reduce image "weight" from VMD

After a VMD rendering it is probable to have a very large image. To reduce its size from several MB to a few MB just open it in Inkscape and export it to a png without changing the settings.


## Resize image in VMD and render it 
display resize 960 540

the use the following keywords (plus the default ones) in Tachyon  

-aasamples 12 %s -format PNG -o %s.png  -res 1920 1080
