  Pico W:
        Sends HTTP requests to the ESP32-C3 when the button is pressed.

    ESP32-C3:
        Acts as an HTTP server, receives requests from the Pico W, and toggles the LED.

Steps:
ESP32-C3 (Server):

    Acts as an HTTP server to receive the signal to toggle the LED.

Pico W (Client):

    Sends an HTTP request to the ESP32-C3 when the button is pressed.

Pico boot load 
If the Raspberry Pi Pico W is not being detected by your computer during the upload process. Unplug your Pico W from the USB port.
Hold down the BOOTSEL button on the Pico W.
While holding the button, plug the Pico W into the USB port of your computer.
The Pico should now appear as a USB mass storage device named something like RPI-RP2
