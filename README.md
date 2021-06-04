###  SkiROS2 template library

Template of a custom package for [skiros2](https://github.com/RVMI/skiros2).

### Configure steps

* Replace word "template" with your package name:
```
> cd skiros2_template_lib  
> sed -i 's/template/my_pkg_name/' *.*  
```
* Replace word "xyz" with your robot name, in the ```owl``` and ```launch``` folders
```
> sed -i 's/xyz/cobot1/' owl/*.* launch/*.*
```
* Launch main.launch
```
> roslaunch skiros2_template_lib main.launch
```

