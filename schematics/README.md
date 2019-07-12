    This is my personal concept of a small add-on board with a FPGA connected to the Beagleboard-xM with following features :
    Xilinx XC3S500E Spartan 3E FPGA
    Micron M25P40 4Mb SPI Flash configuration memory to store FPGA bit file
    256Mb Synchronous High-Speed CMOS DRAM MT48LC16M16A2P-7E, 16Mb x 16Bit x 4 Banks
    ATmega328 8-bit 8Mhz AVR Microcontroller
    ADC TI-ADS5522 12 bits / 80 Mhz with SMA conn. input
    DAC Analog Devices AD9764 TxDAC 14 bits / 125 Mhz with SMA conn. output
    50 MHz crystal oscillator and 125 Mhz crystal oscillator
    Linear Tech LTC6904 I2C 10kHz-68MHz programmable CMOS clock oscillator
    I2C EEPROM 24Cxx
    Mini Circuits ADEX-10L Modulator / Demodulator 
    Analog Devices ADF4350 Hi-Frequency PLL RF Signal Source Generator 
    NXP SGTL5000 Ultra-Low-Power Audio Codec
    3.3V I2C port for off-board serial expansion.
    JTAG port for FPGA development and debugging
    Diagnostic LEDs (2 User defined, 2 Configuration status, 1 live led)
    Powered by DC 5V (voltage source level) / 3.3V (all devices io level) / 1.8V (beagleboard-xm signal level)
