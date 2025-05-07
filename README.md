### Hi there 👋, I'm Quang Trinh;

[![tkhquang.dev](https://img.shields.io/static/v1?label=tkhquang.dev&message=%20&color=cyan&logo=&style=flat-square&logoColor=white)](https://tkhquang.dev)
[![me@tkhquang](https://img.shields.io/static/v1?label=me@tkhquang&message=%20&color=red&logo=gmail&style=flat-square&logoColor=white)](mailto:khacquang.trinh@gmail.com)
[![tkhquang](https://komarev.com/ghpvc/?username=tkhquang)](https://github.com/tkhquang)


```gas
# -------------------------------------------------------------------
# Quang's Dual-Core Loader
# -------------------------------------------------------------------

.section .data
    id_string:      .asciz "Quang | FE Day, RE Night | Age: 30+"
    day_focus:      .asciz "Day: React, Elixir/Phoenix -> Crafting UIs that sparkle"
    switch_msg:     .asciz "Switching Modes... (Caffeine levels critical)"
    night_focus:    .asciz "Night: C++, Rust, Ghidra -> Unraveling binary mysteries"
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
