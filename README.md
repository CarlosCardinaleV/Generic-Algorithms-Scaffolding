# Genetic Algorithms Image Generation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


This project is a genetic algorithm-based image generation system that creates random images and estimates their similarity by comparing pixel-by-pixel color values. The lower the similarity score, the more similar the images are.

## Table of Contents
- [Genetic Algorithms Image Generation](#genetic-algorithms-image-generation)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Code Structure](#code-structure)
  - [How to Use](#how-to-use)
  - [Issues](#issues)
  - [Contributing](#contributing)

## Project Overview

This project consists of HTML, JavaScript, and canvas elements to demonstrate a genetic algorithm for image generation. Here's a brief overview of the key components:

- **Figura**: A constructor function to create figure objects with type, x, and y coordinates.

- **Individuo**: A constructor function to create individual objects with DNA represented as an array of Figura objects.

- **shuffleArray**: A utility function to shuffle an array randomly.

- **CrearPoblaciónInicial**: Function to create an initial population of individuals with randomized DNA.

- **Cruzar**: Function to cross DNA between two individuals to create a new one.

- **Mutar**: Function to mutate an individual's DNA by modifying random elements.

- **calcularAmplitud**: A function to calculate the amplitude of an individual (functionality is incomplete).

- **seleccion**: Function to select the best individuals in a population based on their score.

- **getImage**: Function to create images with random shapes (circles, rectangles, lines) for comparison.

- **drawCircle**: Helper function to draw a circle on the canvas.

- **drawLine**: Helper function to draw a line on the canvas.

- **drawRectangle**: Helper function to draw a rectangle on the canvas.

- **similarity**: Function to calculate the similarity between two images based on pixel color values.

## Code Structure

The code is structured as an HTML page containing JavaScript functions. The genetic algorithm workflow includes creating and evolving a population of individuals represented by their DNA. The canvas is used to render images, and a table displays image similarities.

## How to Use

1. Open the HTML file in a web browser.

2. The code will load an image from an external source (defined by `src`) and create an initial population of individuals. The canvas will display the loaded image, and the table will show image similarities.

3. The genetic algorithm runs, and you can observe the evolution of images and their similarities in the table.

4. The code provides options to cross individuals, mutate their DNA, and select the best candidates. You can explore and modify the genetic algorithm parameters and functions as needed.

## Issues

The code has some issues and incomplete functionality:
- The `calcularAmplitud` function is incomplete, and its purpose is not fully clear.
- The code lacks user interface for interaction or control over the genetic algorithm parameters.
- Some aspects of the genetic algorithm might need further tuning and optimization.

## Contributing

If you're interested in contributing to this project or have suggestions for improvements, please feel free to fork the repository and submit pull requests or issues.

Feel free to explore and modify the code to suit your needs and experiment with genetic algorithms for image generation.
