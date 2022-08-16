# binary-classification

## Intro

Learning objectives:
  * Convert a regression question into a classification question.
  * Modify the classification threshold and determine how that modification influences the model.
  * Experiment with different classification metrics to determine your model's effectiveness.

## Usage

### Running code cells
You must run code cells in order. In other words, you may only run a code cell once all the code cells preceding it have already been run.

To run a code cell:

1. Place the cursor anywhere inside the [ ] area at the top left of a code cell. The area inside the [ ] will display an arrow.
2. Click the arrow.
Alternatively, you may invoke Runtime->Run all. Note, though, that some of the code cells will fail because not all the coding is complete.

### Why did you see an error?
If a code cell returns an error when you run it, consider two common problems:

1. You didn't run all of the code cells preceding the current code cell.
2. If the code cell is labeled as a Task, then you haven't written the necessary code.

### Use the right version of TensorFlow
The following hidden code cell ensures that the Colab will run on TensorFlow 2.X, which is the most recent version of TensorFlow:
```python 
%tensorflow_version 2.x
```

## Definition

### 1. Build and train a model function
  * `create_model(my_learning_rate, feature_layer, my_metrics)`, which defines the model's topography.
  * `train_model(model, dataset, epochs, label_name, batch_size, shuffle)`, uses input features and labels to train the model.

### 2. Plotting function
  * `plot_curve(epochs, hist, list_of_metrics)`, show how various classification metrics change with each epoch.

## Document
Google LLC 2020

