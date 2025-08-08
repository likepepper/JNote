# 插件系统 - pf4j-spring

## 扩展点 - ExtensionPoint

扩展点是插件系统的核心，它定义了插件可以扩展的功能点。扩展点通常是一个接口，插件实现这个接口，即可扩展主程序的功能。

```java
public interface GreetingExtensionPoint extends ExtensionPoint {
    /**
     * 打招呼
     */
    void sayHello();
}
```
