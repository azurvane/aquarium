# Arduino Virtual Aquarium

https://github.com/YourUsername/YourRepo/assets/12345/video_file.mp4


This project turns an Arduino and an OLED screen into a digital fish tank. It features a swimming fish, bubbles, and swaying seaweed.

### What it does

* **Swimming Fish:** A fish moves across the screen. When it hits the edge, it flips around and swims back.
* **Triangle Bubbles:** Every now and then, the fish "breathes" out a group of three bubbles in a triangle shape. These float to the top on their own.
* **Swaying Seaweed:** There are two plants at the bottom. One is big and one is small, and they both wave back and forth.
* **Smart Memory:** The animations are stored in a way that doesn't slow down the Arduino.

### What you need

* **Arduino Uno**
* **SSD1306 OLED Screen** (128x64 pixels)
* **4 Jumper Wires**

### How to wire it

Check the image in the `readme_images` folder called `circuit.png` to see where the wires go. Usually, it looks like this:

* **VCC** to 5V
* **GND** to Ground
* **SDA** to A4
* **SCL** to A5

### How to use it

1. Make sure you have the **Adafruit GFX** and **SSD1306** libraries installed in your Arduino software.
2. Copy the code into a new sketch.
3. Plug in your Arduino and click **Upload**.
4. Watch your fish swim!

### License

This project is open-source under the **MIT License**.

---