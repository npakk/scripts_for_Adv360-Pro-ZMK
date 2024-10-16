# scripts_for_Adv360-Pro-ZMK

1. 以下のファイルをconfig/配下に追加

- combos.keymap

2. config/adv360.keymapを変更

```diff
/ {
+   #include "combos.keymap"

    behaviors {
      #include "macros.dtsi"
```
