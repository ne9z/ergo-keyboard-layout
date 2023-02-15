This repo contains keyboard layout files in the XKB
format, suitable for use with Sway WM.

Usage
============================================================

In ~/.config/sway/config:

    input "type:keyboard" xkb_file $HOME/.config/sway/keymap_name.xkb

Description
============================================================

en-us-qwerty-original.xkb.txt

    This is the original US qwerty layout without any modification.

en_us-sticky-modifiers-keymap.xkb.txt

    This is the US qwerty layout with sticky modifiers.

en_us-sticky-modifiers-keymap-with-latch-to-lock.xkb.txt

    This is the US qwerty layout with sticky modifiers,
    press modifiers twice will lock them. i.e., press
    Shift twice for shift lock.

swaywm-emacs-ergo-keymap.txt

    This is the US qwerty layout with Ctrl key and
    CapsLock key swapped, designed for Emacs users.

    Other details:
    - Caps Lock → Left Ctrl
    - Apostrophe/Quotation mark → Right Ctrl
    - Tab → Apostrophe/Quotation mark
    - Right Ctrl → Tab (use C-i for Tab)
    - Sticky modifier keys, press two keys together will revert to non-sticky behavior.
    - Press modifier keys twice to cancel sticky behavior.
    - Use Caps Lock indicator for sticky modifier status.
