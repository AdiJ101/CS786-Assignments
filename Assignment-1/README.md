# CS786 Assignment 1: Hopfield Network Simulation

This project explores the implementation and analysis of Hopfield Networks, a form of recurrent neural network, through various simulations and experiments. The notebook demonstrates the memory capacity, error correction, and retrieval capabilities of Hopfield Networks using different variations and datasets.

## Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Structure](#structure)
- [Usage](#usage)
- [Results](#results)
- [Merits and Demerits](#merits-and-demerits)
- [Contributors](#contributors)

## Introduction

Hopfield Networks are neural networks designed for associative memory tasks. They can retrieve stored patterns even when provided with noisy or incomplete inputs. This assignment delves into the dynamics and capacity of these networks by using binary patterns and exploring their performance under different conditions.

## Objectives

1. Implement a basic Hopfield Network model and an integrate-and-fire neuron model.
2. Analyze the network’s performance in the following scenarios:
   - **Varying the informativeness of the cue.**
   - **Varying the number of stored patterns.**
   - **Varying the size of the network.**
3. Study the effectiveness of the Hopfield Network classifier using the MNIST dataset.

## Structure

1. **Integrate-and-Fire Neuron Model**: Implementation and explanation of the basic neuron model.
2. **Hopfield Network Model**: Construction and simulation of the Hopfield Network.
3. **Q1**: Explanation and experiment using the basic Hopfield Network.
4. **Our Own Hopfield Network Model**: Custom implementation for detailed analysis.
5. **Experiments**:
   - **Varying Informativeness of the Cue (a)**
   - **Varying the Number of Stored Patterns (b)**
   - **Varying the Size of the Network (c)**
6. **Q3 and Q4**: Analysis of retrieval accuracy and comparison of theoretical versus experimental results.
7. **Classifier Implementation**: Implementing a Hopfield Network classifier on MNIST data.

## Usage

1. **Clone the repository**:
   ```bash
   git clone <repository-link>
   cd <repository-directory>
