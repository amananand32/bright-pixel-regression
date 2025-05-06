Project Workflow:

    1.Dataset Generation

    Randomly generate 50x50 images with one white pixel (255) and others black (0).

    Saving the corresponding coordinates of the white pixel as the target (x, y).

    2. Model Architecture

    Use a simple Convolutional Neural Network (CNN) or fully connected model.

    Output layer will have 2 neurons (for x and y), with linear activation.

    3. Training Setup

    Loss function: Mean Squared Error (MSE).

    Evaluation: Plot predicted vs ground truth coordinates.

   4. Visualization

    Showed examples of input image, true vs predicted coordinate.

    Include training/validation loss curves.

   5. Code Quality

    Ensuring clean code with PEP8 formatting and comments
