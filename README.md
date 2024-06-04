# My Speech Recognition App

This is a simple speech recognition application using TensorFlow.js and the Speech Commands model. The app allows users to collect speech data, train a model, and use it for real-time speech recognition.

## Features

- Collect speech data for left, right, and noise commands
- Train a TensorFlow.js model on collected data
- Real-time speech recognition to control a slider

## Files

- `index.html`: The main HTML file that includes buttons for collecting data, training the model, and using the model for speech recognition.
- `index.js`: The JavaScript file that handles data collection, model training, and real-time speech recognition.

## How to Use

1. Open `index.html` in a web browser.
2. Click and hold the buttons (Left, Right, Noise) to collect speech data.
3. Click the Train button to train the model with the collected data.
4. Click the Listen button to start real-time speech recognition.

## Dependencies

- [TensorFlow.js](https://www.tensorflow.org/js)
- [TensorFlow.js Speech Commands Model](https://github.com/tensorflow/tfjs-models/tree/master/speech-commands)

## License

This project is licensed under the MIT License.
