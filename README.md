# strongR-frida-android

Follow [FRIDA](https://github.com/frida/frida) upstream to automatic patch and build an anti-detection version of frida-server for android.

跟随 FRIDA 上游自动修补程序，并为 Android 构建反检测版本的 frida-server。

**Hint: Don't fork this repository**

## 构建指定版本frida

[创建新的issues](https://github.com/anjia0532/strongR-frida-android/issues/new/choose) 选择 `New Version` 模板

标题格式为 `[VERSION]frida版本号`，别自己瞎搞，以 [https://github.com/frida/frida/tags](https://github.com/frida/frida/tags) 为准,一般类似 `15.1.19` 这样

可以参考 [已有请求编译版本集锦](https://github.com/anjia0532/strongR-frida-android/issues?q=is%3Aissue+label%3Aversion+)

## Patchs

[Git Patch Files](https://github.com/AAAA-Project/Patchs/tree/master/strongR-frida/frida-core)

|module|name|
|-|-|
|frida-core|0001-string_frida_rpc.patch|
|frida-core|0002-io_re_frida_server.patch|
|frida-core|0003-pipe_linjector.patch|
|frida-core|0004-io_frida_agent_so.patch|
|frida-core|0005-symbol_frida_agent_main.patch|
|frida-core|0006-thread_gum_js_loop.patch|
|frida-core|0007-thread_gmain.patch|
|frida-core|0008-protocol_unexpected_command.patch|

## Download

[Latest Release](https://github.com/anjia0532/strongR-frida-android/releases/latest)

## References

- [https://github.com/feicong/strong-frida](https://github.com/feicong/strong-frida)
- [https://github.com/qtfreet00/AntiFrida](https://github.com/qtfreet00/AntiFrida)
- [https://t.zsxq.com/miIunQN](https://t.zsxq.com/miIunQN)
- [https://github.com/darvincisec/DetectFrida](https://github.com/darvincisec/DetectFrida)
- [https://github.com/b-mueller/frida-detection-demo](https://github.com/b-mueller/frida-detection-demo)

## Thanks

- [@feicong](https://github.com/feicong)
- [@r0ysue](https://github.com/r0ysue)
- [@hellodword](https://github.com/hellodword)
- [@qtfreet00](https://github.com/qtfreet00)

## Discussion

<img src="img/1.png" width = "200" height = "260" alt="" align=center />

## Advert

<img src="img/2.png" width = "180" height = "240" alt="" align=center />

<img src="img/3.png" width = "180" height = "240" alt="" align=center />
