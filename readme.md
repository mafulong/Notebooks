# 插件开发
目前
- java11
- gradle 6.7 不用提前安,idea有

1. git clone
2. idea开发，设置sdk为opensdk java11
3. 点进build.gradle的run-ide进行本地测试。它就是起了个新idea只有你这个插件，然后你手动测试。

# 生成plugin的jar包

intellij里的buildPlugin是不包含的dep jar包的，用不了

run shadowJar这个命令。
