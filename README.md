# Ɛ𖣐 (Emerald) Programming Language

## Overview

**Ɛ𖣐 (Emerald)** is a low-level, high-complexity programming language developed by Emeralds Inc. It is engineered for direct processor execution, system kernel development, and the creation of native Linux binaries. The language is defined by its extreme verbosity and architectural proximity to hardware.

The design philosophy of Ɛ𖣐 prioritizes granular control over abstraction. A simple "Hello World" implementation requires over 200 lines of code, as the language mandates manual memory management, register manipulation, and binary-encoded character output.

## Technical Specifications

* **File Extension:** `.estx`
* **Execution Model:** Direct processor execution / Native Linux Binary
* **Paradigm:** Low-level Imperative / Binary-Structural
* **Instruction Set:** Over 1,000 unique commands
* **IDE:** Elementary (Custom environment for Ɛ𖣐 development)

## Core Mechanics

### Binary Character Encoding

The Ɛ𖣐 compiler does not accept standard ASCII or UTF-8 string literals for processing. Every character, digit, or symbol must be provided in its 8-bit binary representation. Failure to do so results in an immediate `SyntaxError`.

For example, to output "H", the source must contain the binary sequence: `01001000`.

### GUI Subsystem

Despite its low-level nature, Ɛ𖣐 supports a dedicated graphical library known as `gui`. This allows developers to construct windows, icons, and interactive elements. While similar in capability to Python's Tkinter, the Ɛ𖣐 implementation requires manual byte-mapping for every visual component.

## The Elementary IDE

The official development environment, **Elementary**, features a high-contrast interface:

* **Primary Theme:** Deep Black background with Lime Green accents.
* **Make Bin Utility:** A specialized Linux-only feature that compiles `.estx` source directly into a standalone binary executable, similar to the behavior of PyInstaller but utilizing native Ɛ𖣐 compilation logic.
* **BIN ⟨⟩ Text Utility:** A live conversion tool integrated into the IDE to assist developers in translating standard text into the mandatory binary format required by the compiler.
* **Error Diagnostics:** Advanced syntax highlighting and underline-based error reporting that pinpoints the exact line and bit-sequence causing an execution failure.

## Commands and Syntax

The instruction set contains over 1,000 commands. All commands are strictly lowercase. The logic follows a pseudo-assembly structure where data movement, arithmetic, and system calls require explicit register addressing.

**Example Syntax Logic:**

* Functions and execution calls must precede the binary data.
* Textual comments or metadata are encapsulated in asterisks: `*Comment Example*`.
* Direct hardware interrupts are used for all I/O operations.

## Installation and Compatibility

### Linux

* Supports full binary compilation via the `Make Bin` feature.
* Full terminal integration and execution of generated binaries.

### Windows

* Supports the Elementary IDE for code writing and debugging.
* `Make Bin` functionality is disabled; execution is handled within the IDE environment.

## License and Restrictions

**No License.**

All rights are reserved by Emeralds Inc.

* **Copying is strictly prohibited.**
* The redistribution of source code, binaries, or the Ɛ𖣐 compiler logic is not permitted.
* Unauthorized use of the Ɛ𖣐 trademark or the Elementary IDE interface design is forbidden.
