# mylibrary
library版本库

##在project目录的build.gradle中添加：
```
repositories {
        //指定Github路径，mylibrary项目
        maven { url "https://github.com/zlzlzl19880408/mylibrary/raw/master" }
    }
```
##引入方式，在app/build.gradle下配置：
```
implementation 'com.example:mylibrary:1.0.0'
```

