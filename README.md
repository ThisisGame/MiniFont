# MiniFont
generate mininal ttf font file.

# Code By Google
MiniFont is Changed From sfntly,sfntly is a font editor tool code by google.
sfntly can use to generator mininal ttf font file,use like 
```
 java -jar sfnttool.jar  -s "中国造" MicrosoftHeiti.ttf msyh_simplify11.ttf
```

but cannot load data from txt file,so i make some change.

# build
Clone this repository,then use ant to build.
![image](https://github.com/ThisisGame/MiniFont/blob/master/doc/1.png)

you can find it in
```
dist\tools\sfnttool\sfnttool.jar
```


# usage
```
 java -jar sfnttool.jar  -s "中国造" MicrosoftHeiti.ttf msyh_simplify11.ttf
 java -jar sfnttool.jar  -s "1.txt" MicrosoftHeiti.ttf msyh_simplify11.ttf
```

![image](https://github.com/ThisisGame/MiniFont/blob/master/doc/2.png)


# notices
ant1.10 need java1.8, if you pc run java1.7,choose ant 1.09

ant need tools.jar,you need copy from C:\Program Files\Java\jdk1.7.0_80\lib to C:\Program Files\Java\jre7\lib

如果是中文，txt要设置对应编码

![image](https://github.com/ThisisGame/MiniFont/blob/master/doc/3.png)
