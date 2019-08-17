babi
====

a text editor, eventually...

### why is it called babi?

I usually use the text editor `nano`, frequently I typo this.  on a qwerty
keyboard, when the right hand is shifted left by one, `nano` becomes `babi`.

### quitting babi

currently you can quit `babi` by using `^X` (or `^C` which triggers a
backtrace).

## demos

not much works yet, here's a few things

### color test (`babi --color-test`)

this is just to demo color support, this test mode will probably be deleted
eventually.  it uses a little trick to invert foreground and background to
get all of the color combinations.  there's one additional color not in this
grid which is the "inverted default"

![](https://i.fluffy.cc/rwdVdMsmZGDZrsT2qVlZHL5Z0XGj9v5v.png)

### file view

this opens the file and displays it but it isn't editable yet.  movement is
currently enabled through the arrow keys and some key combinations are
detected.  unknown keys are displayed as errors in the status bar.  babi will
scroll if the cursor goes off screen either from resize events or from
movement.

![](https://i.fluffy.cc/14Xc4hZg87CBnRBPGgFTKWbQFXFDmmwx.png)

![](https://i.fluffy.cc/wLvTm86lbLnjBgF0WtVQpsxW90QbJwz5.png)
