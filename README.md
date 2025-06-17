### Hi there 👋, I'm Quang Trinh;

[![tkhquang.dev](https://img.shields.io/static/v1?label=tkhquang.dev&message=%20&color=cyan&logo=&style=flat-square&logoColor=white)](https://tkhquang.dev)
[![me@tkhquang](https://img.shields.io/static/v1?label=me@tkhquang&message=%20&color=red&logo=gmail&style=flat-square&logoColor=white)](mailto:khacquang.trinh@gmail.com)
[![tkhquang](https://tkhquang.dev/api/pageviews/badge?pathname=https%3A%2F%2Fgithub.com%2Ftkhquang&label=Profile%20views&v=1)](https://github.com/tkhquang)


```gas
# -------------------------------------------------------------------
# Quang's Dual-Core Loader
# -------------------------------------------------------------------

.section .data
    id_string:      .asciz "Quang | FE Day, RE Night | Age: 30+"
    day_focus:      .asciz "Day: React, Elixir/Phoenix"
    switch_msg:     .asciz "Switching Modes... (Caffeine levels critical)"
    night_focus:    .asciz "Night: C++, Rust, Ghidra"
    system_info:    .asciz "OS: Fedora/Windows | Editors: VSCode/Neovim"
    ethos:          .asciz "Ethos: Pixel Crafter, Binary Decoder"

.section .text
.globl _start

_start:
    # --- Boot: The Dev Persona ---
    lea id_string(%rip), %rdi

    # --- Day Shift: Pixel Perfect ---
day_op_engage:
    lea day_focus(%rip), %rsi
    # call ExecuteDayRoutine

    # --- The Flip: Code Twilight Zone ---
    lea switch_msg(%rip), %rdx
    int $0x13           # The context switch!

    # --- Night Shift: Binary Deep Dive ---
night_op_engage:
    lea night_focus(%rip), %rcx
    # call ExecuteNightRoutine

    # --- System Constants ---
    lea system_info(%rip), %r8
    lea ethos(%rip), %r9

    # --- The Loop & Recharge ---
loop_point:
    call CreateImproveLearnRepeat  # The cycle of development
    call Recharge                  # Keep the energy flowing
    jmp loop_point

    # --- Routines ---
CreateImproveLearnRepeat:
    # Code would go here
    ret

Recharge:
    # Consume Coke, walk Doggo, repeat
    ret

    # --- Developer's Motto / Parting Thought ---
    # "Shine the UI, x-ray the binary."
```

***

**☕ Powering the Next `int $0x13`?**

Most of my time is spent either fine-tuning interfaces or reverse-engineering the weird and wonderful bits of software. It's all part of the fun, and fueled by curiosity (and caffeine).

If you liked something I made or just want to support the ongoing tinkering, a virtual coffee is always appreciated!

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/tkhquang)

<sup>Or, if you prefer ko-fi: <https://ko-fi.com/tkhquang></sup>
