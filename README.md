
# Calculate the distance between points in curved surface

### Download the library

!pip install data_whiz

### Importing the library

from data_whiz import curved_surface

### HSV_distance

 - HSV_distance is used to Calculate the distance between the HSV color codes.

 - H represents Hue ranges from 0 to 360, S represents Saturation and V represents Value(brightness) both ranges from 0 to 100. 
    - syntax  -   curved_surface.HSV_distance([H1,S1,V1],[H2,S2,V2])
    - example -   curved_surface.HSV_distance([0,0,0],[360,100,100]) 
    
### distance

- distance is used to find the distance between two points or between two list of points in curved surface.
    
        1. This is to find distance between two list of points 
            
            syntax  -   curved_surface.distance([p11,p12,p13],[p21,p22,p23])
            
            example -   curved_surface.distance([0,0,0],[360,360,360])

        2. This is to find distance between two points in the curved surface. 
            
            syntax  -   curved_surface.distance(p1,p2)
            
            example -   curved_surface.distance(0,500)



## License

[MIT](https://choosealicense.com/licenses/mit/)
