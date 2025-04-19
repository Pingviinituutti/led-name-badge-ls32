# templates

``` sh
-m4 -s6  "Hello"
# Animated coffee cup
-m5 "Café:gfx/coffee.png:Café:gfx/coffee2.png:"
-m4 -a1 "Home:HEART:"
-m8 -s8 "Party"
-m6     "Chill"
-m7 -s6  "Tada" 
-m0 -s8 ":gfx/lightning.png:Gotta go fast :gfx/lightning_r.png:"
# long string
python ./led-badge-11x44.py -m"4,5,4,8,6,7,0" -a"0,0,1,0,0,0,0" -s"6,4,4,8,4,6,8" "Hello" "Café:gfx/coffee.png:Café:gfx/coffee2.png:" "Home:HEART:" "Party" "Chill" "Tada" ":gfx/lightning.png:Gotta go fast :gfx/lightning_r.png:"
```
