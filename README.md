# scripts_for_Adv360-Pro-ZMK

> 参考 https://www.bencode.net/posts/kinesis/

1. 以下のファイルをconfig/配下に追加

- extra_morphs.dtsi

2. config/adv360.keymapを変更

```diff
/ {
    behaviors {
      #include "macros.dtsi"
      #include "version.dtsi"
+     #include "extra_morphs.dtsi"
```
