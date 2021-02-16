[Home](index.md)

##### Colored Chat

Using APT you can easily send colored console messages!

In your plugin's main class just simply import 

```java
import static com.aylias.minecraft.plugins.ayliasPluginTools.util.MessageTools.*;
```

And then use this line in `onEnable()`

```java
sendConsoleMessage("-c.r/Red -c.g/Green -c.b/Blue")
```

You should see a message like this in the console when you start your test server (With your plugin name in place of AyliasPluginTools):

![colorconsole_example](colorconsole_example.png)

