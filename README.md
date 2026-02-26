# Guitarist, Developer, ElCapitan

![Static Badge](https://img.shields.io/badge/Language-Underworld%20System%20Commands-gold)

<img height="250" src="https://github.com/at-elcapitan/at-elcapitan/assets/96237569/b64c8e2f-ebfe-4160-bd15-455ef590733b" align="right">

```
SYSTEM CALL
  CONNECT armament
  CONNECT atelcapitan
  SEARCH recollection_info
  EXTRACT core_image
  CONNECT resource
  
  USE primary_information
  APPEND c_code FROM elcapitaninfo/information.c
  MATERIALIZE main_window
  
  RELEASE RECOLLECTION
```

<span style="color:green"> </span>

![Static Badge](https://img.shields.io/badge/Language-NASM%20[ELF32]-darkgreen)
```nasm
  extern printf
  global main
  use32

section .data
  fmt db `Name: %s\nProgramming Languages: %s\nFrameworks: %s\nOS: %s`, 0xA, 0

  name db        `ElCapitan, John`, 0
  progLangs db   `NASM, C, Python, TypeScript`, 0
  frameworks db  `Flask, FastAPI, SQLAlchemy, Vue.js`, 0
  os db          `Arch Linux`, 0

section .text

main: 
  ; pushing arguments to the stack
  push os
  push frameworks
  push progLangs
  push name
  push fmt
  
  call printf

  ; clearing the stack
  add esp, 20

  ; ok, return code is 0, exiting
  xor eax, eax
  ret
```

### ‍💻 The Programmer™

Greetings. I'm Vladislav (also John, whatever) a software developer. Formerly worked with C, but currently (and sadly) aimed at Python, TypeScript and their frameworks. Making dynamic Single-page Applications with Vue.js and backend with FastAPI. More information at my site https://elcapitan.atproject.com.ua or my projects.

### ⛳ My hobbies
- Watching Anime
- Reading books (especially ranobae)
- Playing games
- Coding and gaining skills
- Digging deeper into how computers work
- Creating various visual interfaces
- Exploring the universe

## Contact

E-mail: <elcapitan@atproject.com.ua>
