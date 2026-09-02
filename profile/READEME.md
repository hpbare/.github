# hpbare
Lightweight, platform-independent drivers for embedded peripherals.
Designed to work on any microcontroller without vendor lock-in.

## Design Philosophy
Each driver:
- Has no dependency on any HAL or SDK.
- Uses function pointers for I2C/SPI/UART abstraction.
- Is fully standalone and portable.
- Brings its own platform layer per target.

## Usage
1. Clone the driver that you need.
2. Implement the platform layer.
3. Initialize and use.

See each driver's README for detailed instructions.

## Notes
- Drivers are independent → safe to use individually.
- No shared core or hidden dependencies.
- Suitable for bare-metal, RTOS, embedded platform.

## License
MIT