# sound-synthesis-plugin-python
Sound Synthesis Plugin to modulate the phase of a sound for a Digital Audio Workstation 

# Phase Plugin for Audio Signal Phase Reversal

The **Phase Plugin** is a simple audio plugin designed to reverse the phase of a sound signal. It takes an audio input and processes it to produce an output with its phase inverted. This can create interesting sound effects and spatial modifications in audio tracks.

## Features

- **Phase Reversal:** The plugin processes the audio input, inverting the phase of the sound wave, creating an output where the positive and negative values of the waveform are swapped.

## Getting Started

To use the Phase Plugin, follow these steps:

1. **Installation:** Make sure you have Python installed on your system. Install the required dependencies using the following command:

    ```
    pip install pyaudiounit numpy
    ```

2. **Running the Plugin:** Run the provided Python script `phase_plugin.py` to start the plugin. It will process audio input and produce phase-inverted output.

3. **Adjustment:** You can modify the `GAIN_FACTOR` variable in the script to control the strength of phase inversion.

## Usage

1. Run the `phase_plugin.py` script using Python.

2. Input audio will be processed, and phase-inverted audio will be produced.

3. Adjust the `GAIN_FACTOR` in the script to control the level of phase inversion.

## Contributing

If you're interested in contributing to the Phase Plugin, feel free to fork this repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The Phase Plugin is based on the `pyaudiounit` library, which provides access to Audio Units and enables audio processing capabilities in Python. The code is intended as a basic demonstration of phase reversal and can be extended for more complex audio processing tasks.
