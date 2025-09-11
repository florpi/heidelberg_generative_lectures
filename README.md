# Generative Models: From Theory to Practice

## Why Build from Scratch?

Understanding generative models requires more than just calling APIs or using pre-built libraries. By implementing these models from scratch, you'll develop an intuitive understanding of the mathematical foundations, computational challenges, and design decisions that make modern generative models possible. 

## Course Materials

**[Lecture Slides](https://slides.com/carolcuesta/heidelberg_summer_school)**

## Notebooks & Learning Objectives

### 1. **Box-Muller Transform** (`01_box_muller.ipynb`)
Understand the change of variables rule for probability distributions through a classic example. You'll implement the Box-Muller transform to sample from a Gaussian distribution starting with uniform random variables. **Key Learning:** Computing Jacobians and using them to estimate probability densities p(x) for transformed variables—important for understanding normalizing flows.

### 2. **Continuous Normalizing Flows** (`02_cnf.ipynb`)
Build a continuous-time normalizing flow from scratch using PyTorch to solve the two moons sampling problem. **Key Learning:** Implement neural ODEs, understand the continuous-time perspective on normalizing flows.

### 3. **Flow Matching** (`03_flow_matching.ipynb`)
Implement flow matching for the same two moons problem, comparing this approach to CNFs. **Key Learning:** Understand the flow matching objective, and appreciate the computational advantages over likelihood-based training.

### 4. **Astrophysics Application** (`04_astro_example.ipynb`) ⚠️ *GPU Required*
Apply flow matching to a realistic scientific problem: generating galaxy images. This exercise demonstrates how generative models scale to high-dimensional, real-world data. **Key Learning:** Handle complex datasets, implement conditional generation.

## Getting Help

Complete solutions for all exercises are available in the `solutions` branch. Use these to check your work or get unstuck, but try implementing each concept yourself first.

For the astrophysics example, ensure you have GPU access or use Google Colab with GPU runtime enabled.

