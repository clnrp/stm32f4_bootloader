# stm32f4_bootloader

## bootloader
Flash base address 0x08000000, size = 64Kb "0x10000"

Jump to application Reset_Handler

## application
Flash base address 0x08010000, size = 960Kb

Enable #define USER_VECT_TAB_ADDRESS, and set VECT_TAB_OFFSET = 0x00010000
