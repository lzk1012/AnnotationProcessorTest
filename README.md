# AnnotationProcessorTest
原文档网址：[注解处理器是干嘛的](https://juejin.im/post/6844903889314005005 "注解处理器是干嘛的")

## 使用方式
1. 先处理[AnnotationProcessor](https://github.com/lzk1012/AnnotationProcessorTest/tree/master/AnnotationProcessor "AnnotationProcessor")，进行`mvn clean install`打包
2. 处理[annotationTest](https://github.com/lzk1012/AnnotationProcessorTest/tree/master/annotationTest "annotationTest")，这里面引入了第一步的包，通过`mvn compile`编译进行测试
