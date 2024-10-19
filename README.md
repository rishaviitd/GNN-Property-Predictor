# Graph Neural Network Playground

The **Graph Neural Network Playground** is an interactive tool designed to help users visualize and experiment with Graph Neural Networks (GNNs). Built using TypeScript and d3.js, it provides an intuitive interface to train GNNs on custom datasets and observe model performance in real-time.

Your feedback is highly appreciated! If you have any questions, feature requests, or encounter any bugs, please use the GitHub issues section to report them.

## Features

- **Custom Data Input**: Upload your own graph-based data for training.
- **Real-Time Training & Feedback**: Visualize how the model's performance improves as it trains, and see the loss/error rate diminish over time.
- **Model Persistence**: Save the trained model weights for future use or download them directly from the app.

## Getting Started

Follow the steps below to set up the project locally on your machine.

### Prerequisites

Ensure that you have **Node.js** and **npm** installed on your machine. If not, you can download them [here](https://nodejs.org/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/gnn-playground.git
    ```

2. Navigate into the project directory:
    ```bash
    cd gnn-playground
    ```

3. Install the project dependencies:
    ```bash
    npm i
    ```

### Running the Project

To build and run the project, follow these steps:

1. **Build the Application**:
    ```bash
    npm run build
    ```
    This command will compile the app and place the output in the `dist/` directory.

2. **Serve the Application Locally**:
    ```bash
    npm run serve
    ```
    This will serve the application from the `dist/` directory and automatically open it in your browser.

3. **Faster Development with Auto-Refresh**:
    If you want to work on the project and need a fast edit-refresh cycle, use:
    ```bash
    npm run serve-watch
    ```
    This command will automatically rebuild the project whenever a file is changed and refresh your browser.

## How to Use the Playground

1. **Step 1: Upload Your Data**
    - Upload your custom graph data to train a GNN model on it.

2. **Step 2: Train and Evaluate**
    - Monitor the loss/error rate as the model trains. The playground provides real-time feedback to help you understand model performance.

3. **Step 3: Save Model Weights**
    - Once the model has converged, you can save the trained weights for future use or download them directly.

## License

The code is open-source can be used by anyone. 
---

Happy experimenting with Graph Neural Networks!
