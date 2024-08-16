# TOUCH-SCREEN-CODE-FOR-3.2-TFT-SPI-240x320-v1.0-display

Pin Connection to esp32



TFT_MISO to Pin 19


TFT_MOSI to Pin 23


TFT_SCLK to Pin 22


TFT_CS   to Pin 13  // Chip select control pin


TFT_DC   to Pin 14  // Data Command control pin


TFT_RST  to Pin 18  // Reset pin (could connect to RST pin)


T_D0 to Pin 19 (same with MISO of the screen)


T_DIN to Pin 23 (same with MOSI of the screen)


LED to 3.3v


GND to Ground


VCC to 5v



TOUCH_CS to Pin 5 // Chip select pin (T_CS) of touch screen



In the code change " #define REPEAT_CAL true " to " #define REPEAT_CAL false "   to run the touch calibration once
