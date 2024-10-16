# scripts_for_Adv360-Pro-ZMK

1. 以下のファイルをconfig/配下に追加

- combos.keymap

2. config/adv360.keymapを以下の様に変更

```
/* 変更前 */
/ {
        behaviors {
          #include "macros.dtsi"

/* 変更後 */
/ {
    #include "combos.keymap"

    behaviors {
      #include "macros.dtsi"
```
