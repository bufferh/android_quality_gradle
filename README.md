# android_quality_gradle

for android studio
将config目当放到项目的同级目录（与app目录并列）， 
在app的build.gradle 中添加 apply from: '../config/quality.gradle'

执行gradle check 命令会检查checkstyle pmd findbugs lint
也可以单独执行其中一个， 如 gradle checkstyle
