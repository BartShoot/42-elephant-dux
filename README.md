I will be documenting designing my fully custom split keyboard mostly for myself to keep track what I looked into and what I decided as I'm guessing it will take months to finalize it.

# Layout

That is probably the hardest and most important decision for ergonomics. After reading about [risk of thumb injuries](https://getreuer.info/posts/keyboards/thumb-ergo/index.html) I decided agains Corne as it requires you to tuckyour thumb inward too much. Direction of [Elephant42](https://github.com/illness072/elephant42) looks but removing innermost button, moving existing row up and adding second row as my thumb mobility allows it. For other fingers [A. dux](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux) matched closely to what I got from using [ergopad generator](https://pashutk.com/ergopad/). I'll me just moving pinky column upwards.

![Ergopad output](/Images/ergopad.jpg)

For generating layout with starting points for my pcb, plate etc I'll be using [Ergogen project](https://github.com/ergogen/ergogen) that can generate a lot of things for you with just `keyboard.yml` input. Current version still doesn't have correct spacings etc but shows rough idea of what I want to create.

![Initial layout](/Images/initial.dxf)
