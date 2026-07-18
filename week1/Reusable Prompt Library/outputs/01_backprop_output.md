- **Core Mechanism**: **Backpropagation** calculates the gradient of the loss function with respect to each weight in a neural network. It uses the calculus **chain rule** to pass error margins backward from the output layer to the input layer, allowing the model to minimize error.
- **Key Takeaways**:
  * It computes internal errors sequentially to adjust network **weights** and **biases**.
  * It powers iterative optimization algorithms like **Gradient Descent**.
- **Analogy**: Imagine shooting an arrow blindfolded. A friend looks at where it landed and tells you how many feet you missed the target by. You use that feedback to adjust your stance backward before taking the next shot.