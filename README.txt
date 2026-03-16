Blink Homework (BSM316 - Embedded Systems)

This repository contains Homework 1 implementation for STM32F103C8T6 (Blue Pill).

Homework summary
- Generate starter project with STM32CubeMX (SWD + User LED).
- Open project in VS Code.
- Implement LED blink with 1 second period (500 ms ON / 500 ms OFF).
- Build the project and produce firmware files.
- Program MCU flash and verify LED operation.
- Debug with breakpoint on LED-change line and continue multiple times.
- Upload project to GitHub after removing build artifacts.
- Record and upload demonstration video to YouTube.

Implemented blink logic
- File: Core/Src/main.c
- LED toggle function: HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_13)
- Delay: HAL_Delay(500)

Build and program
- Build: make
- Program (OpenOCD): use VS Code task "Program Memory"

Submission notes
- Fill the official homework form with:
  - Name + student number
  - Answers for question items (a-e)
  - GitHub repository link
  - YouTube video link
