# Mouse upside down in VM
https://www.reddit.com/r/swaywm/comments/tsljeo/problem_with_pointer_orientation/

## Solution:
>For me the issue was caused by QEMU. -vga qxl fixed it for me.
>
>This also removed the cursor completely, but it can be added with export WLR_NO_HARDWARE_CURSORS=1.