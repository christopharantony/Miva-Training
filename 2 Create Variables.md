# Create Variable
[Official Training Video](https://docs.miva.com/videos/assign-eval)
![WhatsApp Image 2022-09-23 at 11 00 56 AM](https://user-images.githubusercontent.com/99424113/192264309-212f76c1-457a-4e9f-a363-7ee2a0e3df44.jpeg)

First line is for creating variable.  
Second line is an entity. Entity only for output.
## Let's Practice
Take admin side => Search Sale => Select Categories => sale => Header & Footer => Header
```html
<mvt:assign name="g.name" value=" 'String' " /> 
&mvt:global:name;
<mvt:eval expr="g.name" />
```

![image](https://user-images.githubusercontent.com/99424113/192261275-f8695e19-0104-496a-a0d1-7b74f1f74061.png)

Take user side ( Miva Storefront ) => Select Sale   
![image](https://user-images.githubusercontent.com/99424113/192263415-d9e3f1fb-0d74-4239-80b5-35a391b2d4cf.png)

### Click the Sale you can see the variable there.  
![image](https://user-images.githubusercontent.com/99424113/192263721-0911add0-c3e2-4fee-bbf8-037ae73e9816.png)

Practice more like this.😉
```html
<mvt:assign name="g.name" value="'Christophar Antony'" />
<mvt:assign name="g.length" value=" 100 - len(g.name) $ ' Left in 100'" />
&mvt:global:length;
&mvt:global:name;
```
