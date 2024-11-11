---
{"dg-publish":true,"permalink":"/readme/","tags":["gardenEntry"]}
---


# Mecocoa ![LOGO](/img/user/rsource/logo/MCCA20240501.png) 

- **type**: Operating System
- **domain**: [mecocoa.org](http://mecocoa.org/) 
- **repository** : [GitHub](https://github.com/dosconio/mecocoa)  @dosconio
- **alias**: Kasa-x86
- **license**: BSD-3-Clause license
- **architecture**: Intel-x86(586+), RISC-V-64


## 00-Components

A module can exist as multi-language versions, like `.h&.inc`, or `.c&.cpp&.rs`

| Program   | Format  | Environment    | Description |
| --------- | ------- | -------------- | ----------- |
| USYM BOOT | FLAT A  | 386+           |             |
| Kernel    | ELF A+C | Real16->Flap32 |             |
| Shell16   | ELF C   | Real-16        |             |
| Shell32   | ELF C++ | Flap-32        | (to COTLAB) |

| Root Folder | Description                                    |
| ----------- | ---------------------------------------------- |
| cocheck     |                                                |
| coshell     |                                                |
| depends     | Dependence besides [UNISYM](http://unisym.org) |
| include     |                                                |
| mecocoa     |                                                |
| rsource     |                                                |
| userkit     |                                                |
| configs     |                                                |
| demonst     |                                                |
| documnt     |                                                |
| license     |                                                |
| subapps     |                                                |

## [01-Memory](01-Memory.md) 

## [02-Timelogic](02-Timelogic.md)

## [03-Demonstrations](documnt/03-Demonstrations.md) 

## [04-Routines](documnt/04-Routines.md)

## [05-User](05-User.md)

## 06-Glossary

### Architecture

- `x86`
- `r64` RISC-V64
- `m64` *kept for Dinah* 

