# graphite-ru-34
A writing-focused 34-key ZMK/Linux layout for the graphite and йцукен layouts with mouse keys.

In Linux, set compose to pause, switch lang to lwin.
Instructions on what to do with the [graphite](https://github.com/stozi/graphite-ru-34/blob/main/graphite), [evdev_section](https://github.com/stozi/graphite-ru-34/blob/main/evdev_section.xml), and optionally (for CLI) [graphite.map](https://github.com/stozi/galite-ru-34/blob/main/graphite.map) files are in those files. Copy the contents of [my ZMK keymap](https://github.com/stozi/zmk-config/blob/master/config/a_dux.keymap) file to yours in Github. [ZMK mouse keys](https://zmk.dev/docs/keymaps/behaviors/mouse-emulation) require additional setup.


Prefix 'C' means ctrl+, 'S' means shift+.

Illustration:

Base layer, mouse keys on the left.

```
pgu sal pst cpy cut   esc tab vo- vo+ mut

msl msu msd msr br+   Cbk arl ard aru arr  (msl+msr=scroll up, msu+msd=scroll down)

pgd rmb mmb lmb br-   Cdl the end hom .,

layer2 layer1/enter  shift/space alt/bkspc   
```

Hybrid ctrl/fn layer for base layer (skC is sticky ctrl, Cer is ctrl-enter).

```
F9  F10 F1  F2  F3  F4  F5  F6  F7  F8

rep Cpu Cpd Cer C=  SCb Cal Cad Cau Car

and rdo udo skC C-  SCd F11 Ced Chm F12

null layer0/enter  shift/space alt/del
```
Here and in the next layer you'll see some simple but unusual customizations for puncts.
```
b   l   d   w   z     '"  f   o   u   j
й   ц   у   к   е     н   г   ш   щ   з

n   r   t   s   g     y   h   a   e   i
ф   ы   в   а   п     р   о   л   д   ж

x   q   m   c   v     k   p   .?  -_  ,/ 
я   ч   с   м   и     т   ь   б   ю   .,

layer0 layer3/enter  shift/space alt/bkspc
```
Fn layer for alpha layer. 'cmp' is compose, 'lng' switch lang. Accessed by holding down the left-left thumb key or tapping both left-hand thumb keys at once. Might be nice to have the square brackets right under 9 and 0, but a bigger priority for me is Russian Х (and Э) on a good finger. Ъ and Ё are very rare. This layer could become more symmetrical with more punct customization in the Linux keymap, but I'm not convinced it's worth it.
```
n/a ()  <>  lng n/a  n/a com [{  ]}  n/a
                             х   ъ

9(  0)  1!  2@  3#   4$  5%  6^  7&  8*
9(  0)  1!  2"  3№   4;  5%  6:  7?  8*

\|  ~`  :;  skC cmp  n/a the =+  –— sen
    ё   э

null layer2/enter  shift/space alt/del
```
