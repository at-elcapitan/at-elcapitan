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

<img width="400" src="https://github.com/at-elcapitan/at-elcapitan/blob/4123a794c373f26ba0674228fff64471a51af4ec/alice.gif" align="right"/>

Greetings. As you have already understood, I am Vladislav/John, a software developer. I have been programming for more than 5 years, but actively for the last 3 years. I am interested in the topic of AI and in the future, I want to become one of the AGI developers.

### ⛳ My hobbies
- Watching Anime and reading Ranobae
- Playing games
- Coding and gaining skills
- Digging deeper into how computers work
- Also, [#RussiaFuckedUp](https://music.youtube.com/watch?v=XvxELVB9AO0)

## Contact

E-mail: <elcapitan@atproject.com.ua>

### World [ADO](https://x.com/ado1024imokenp) Domiation!
### World [Yoshino](https://x.com/yoshino_msc) Domiation!
