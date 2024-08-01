# Introduction

I will be documenting designing my fully custom split keyboard mostly for myself to keep track what I looked into and what I decided as I'm guessing it will take months to finalize it.

# Layout

That is probably the hardest and most important decision for ergonomics. After reading about [risk of thumb injuries](https://getreuer.info/posts/keyboards/thumb-ergo/index.html) I decided agains Corne as it requires you to tuck your thumb inward too much. Direction of [Elephant42](https://github.com/illness072/elephant42) looks but removing innermost button, moving existing row up and adding second row as my thumb mobility allows it. For other fingers [A. dux](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux) matched closely to what I got from using [ergopad generator](https://pashutk.com/ergopad/). I'll me just moving pinky column upwards.

![Ergopad output](/Images/ergopad.jpg)

For generating layout with starting points for my pcb, plate etc I'll be using [Ergogen project](https://github.com/ergogen/ergogen) that can generate a lot of things for you with just `keyboard.yml` input. Current version still doesn't have correct spacings etc but shows rough idea of what I want to create.

![Initial layout](/Images/initial.dxf)

## 2nd iteration

I've decided to add another pinky column and one row for numbers+symbols on default layer. Also I got rid of one thumb row, on flat keyboard it just doesn't feel right. If I had to have 6 thumb keys I'd make them angled so it's easier to press.

## Prototype

The 3D model is finished and ready to print!

![Render from fusion](/Images/render.PNG)

There are 4 elements - top cover, plate, walls and bottom. Plate is supposed to sit sandwiched between top and walls with gaskets. Bottom is where MCU, reset and power switch will be located - there is no battery mount so far.

# Case, switches and materials considerations

Ideally I'd like this to be really quiet but prefer tactile switches so I could bring this to work and still have satisfying typing experience.

The case will be completly 3D printed. The switches I picked are `Outemu Silent Cream Yellow`. Really smooth and silent switch with satisfying bump right at the top of the travel distance.

The microcontrollers used in this project will be [nrf-52840](https://github.com/joric/nrfmicro/wiki/Alternatives#supermini-nrf52840)

Stl files can be found and downloaded in `/Models` folder.
