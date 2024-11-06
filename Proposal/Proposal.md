# Proposal: Sound Necklace – A Wearable Musical Instrument

## Introduction

The **Sound Necklace** is a wearable instrument designed to allow users to create and control synthesizer sounds through simple hand gestures, such as touch and proximity. Worn around the neck, this necklace incorporates three primary sensors: **ultrasonic sensors, pressure sensors,** and **touch sensors**. These sensors activate real-time sound manipulation by detecting hand distance, press intensity, and touch. The instrument’s output will connect to **MAX** via **Teensy**, which translates sensor data into various parameters. This setup allows users to create music through intuitive, body-based interactions, making the Sound Necklace both an expressive musical instrument and an accessible interface for beginners.

## Implementation

The Sound Necklace will be realized by mounting the sensors and the **Teensy 4.0 microcontroller** in a compact pendant-like housing. The **ultrasonic sensor** will be placed on the front to measure hand distance for adjusting volume. The **pressure sensor** on the side will trigger different distortion or reverb values based on press force. A **touch sensor** positioned on the back of the pendant will allow users to switch between different types of synthesizers or sound effects.

## Deliverables

### Good Outcome
- Accurate detection and real-time translation of hand distance into volume control using the ultrasonic sensor.
- Pressure-based intensity control to change the distortion parameter.
- Basic touch-based switching for activating different synth sounds.

### Better Outcome
- Integration of an **accelerometer** to map necklace movement to additional parameters.
- Smooth transitions between sounds using the touch sensor.
- Addition of more sound effects like **delay** and **chorus** to enhance the user experience.

### Best Outcome
- Dynamic **LED feedback system** for visual interaction cues.
- Expanded touch functionality, such as double-tap for reverb and hold for delay.
- Minimal latency for a performance-ready instrument.
- Precise control over all parameters.

## Next Steps and Required Skills

To achieve an optimal realization of the Sound Necklace design, I need to focus on the following areas:

1. **Compact Design:** Embedding multiple sensors into a portable, aesthetic necklace form.
2. **Efficient Connection:** Finding the easiest way to connect the breadboard, Teensy, and various sensors.
3. **Code Organization:** Structuring the code in **Arduino IDE** for each sensor effectively to allow for future adjustments.
4. **Data Transmission and Processing:** Learning to code for sensor connections to **Arduino** and transmitting data to **MAX**. I will also need to select processing effects such as **reverb, delay,** and **distortion** and link them to sensor parameters for precise user control.

