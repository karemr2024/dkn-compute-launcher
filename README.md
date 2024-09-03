<p align="center">
  <img src="https://raw.githubusercontent.com/firstbatchxyz/dria-js-client/master/logo.svg" alt="logo" width="142">
</p>

<h1 align="center">
  Dria Compute Node - Launcher
</h1>
<p align="center">
  <i>Dria Compute Node Launcher for easily starting the node.</i>
</p>

## About

This repository contains the CLI application for the [DKN Compute Node](https://github.com/firstbatchxyz/dkn-compute-node). It provides a simple and efficient way to set up and run the Dria Compute Node. The launcher handles environment setup, model selection, and Docker Compose execution, making it easy to start the node with minimal configuration.

## Features

- **Environment Setup:** Automatically loads and manages environment variables.
- **Model Selection:** Supports both predefined models from OpenAI and Ollama. Users can choose models interactively or via command-line flags.
- **Docker Integration:** Ensures Docker is up and running, checks for necessary files, and pulls the latest node image.
- **Flexible Logging:** Allows setting different logging levels for easier debugging and monitoring.
- **Background/Foreground Modes:** Run the node in either background or foreground mode based on your preference.

## Quick Start

1. **Download the executable**: Simply download the latest executable for your operating system from the [releases page]().

2. **Run the Launcher**: Double-click the executable or run it via the command line. Use `-h` or `--help` to see all available options.

   ```sh
   # macos or linux
   ./start --help

   # windows
   .\start.exe --help
   ```

3. **Select Models**: Choose the models to be used in your node setup. You can pass multiple `-m` or `--model` flags or use the interactive model picker.

4. **Start the Node**: Follow the prompts to complete the setup and start your node.

## More Information

For a detailed guide on running the Dria Compute Node and its full capabilities, please refer to the [DKN Compute Node repository](https://github.com/firstbatchxyz/dkn-compute-node/blob/master/docs/NODE_GUIDE.md).