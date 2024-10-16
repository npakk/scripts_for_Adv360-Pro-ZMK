# scripts_for_Adv360-Pro-ZMK

1. 以下のファイルをconfig/配下に追加

- behaviors.keymap

2. config/adv360.keymapを変更

```diff
/ {
    behaviors {
      #include "macros.dtsi"
      #include "version.dtsi"
+     #include "behaviors.keymap"
```
