# CNN-from-scratch

Made a CNN using numpy for the MNIST Dataset. <br>

The CNN has the following structure:<br>

<ul>
<li>Input Layer: 28x28 grayscale images.</li>
<li>Convolutional Layer: Applies 16 filters of size 3x3.</li>
<li>Hidden Layer: Flattens the output from the convolutional layer and applies a Tanh activation function.</li>
<li>Output Layer: Applies a softmax function to produce a probability distribution over 10 classes (digits 0-9).</li>
</ul>
