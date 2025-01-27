# Unicycle Controllers

This repository showcases a comprehensive study and implementation of various control strategies for a unicycle model. The project explores state error feedback controllers (linear and nonlinear), output error feedback techniques, and strategies for Cartesian and posture regulation. All implementations are developed using MATLAB and Simulink.

---

## Table of Contents

- [Overview](#overview)
- [Control Strategies](#control-strategies)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [References](#references)
- [License](#license)

---

## Overview

The control of unicycle models represents a challenging problem due to their non-holonomic constraints and inherent nonlinear dynamics. This project explores:

1. Linear and nonlinear state error feedback controllers.
2. Output error feedback methods.
3. Cartesian and posture regulation techniques to achieve accurate trajectory following and stabilization.

### Key Features
- Comprehensive analysis of linear and nonlinear control strategies.
- Implementation of both Cartesian and posture regulation approaches.
- Simulations developed entirely in MATLAB and Simulink for high-fidelity testing.

---

## Control Strategies

### 1. State Error Feedback Controllers
- **Linear Controllers**:
  - Utilizes proportional and derivative gains to minimize state errors.
- **Nonlinear Controllers**:
  - Incorporates nonlinear terms to account for the complex dynamics of the unicycle.

### 2. Output Error Feedback Techniques
- Feedback based solely on output errors, ideal for systems where full state measurements are unavailable.

### 3. Cartesian and Posture Regulation
- **Cartesian Regulation**:
  - Focused on achieving precise control over the unicycle's position in a 2D plane.
- **Posture Regulation**:
  - Ensures accurate control over both position and orientation.

---

## Project Structure

The repository is organized as follows:

```
Unicycle_controllers/
├── Controllers/
│   ├── Regulation/
│   ├── Trajectory_Tracking/
├── Trajectory/
├── Presentation/
│   └── Project Overview (slides and reports)
├── ref_data.mat
├── LICENSE
└── README.md
```

### Folder Descriptions
- **Controllers/**:
  - Contains MATLAB scripts and Simulink models for the implemented control strategies.
- **Trajectory/**:
  - Scripts and data files for generating and managing reference trajectories.
- **Presentation/**:
  - Summarizes the methodology, implementation, and results of the project.
- **ref_data.mat**:
  - Stores reference trajectories or simulation parameters.

---

## Getting Started

### Prerequisites
- MATLAB R2021b or later.
- Simulink with Control System Toolbox.

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/1richi1/Unicycle_controllers.git
   cd Unicycle_controllers
   ```
2. Open MATLAB and navigate to the desired folder.

---

## Usage

### Generating Trajectories
1. Go to the `Trajectory/Generation Scripts/` directory.
2. Run the scripts to generate reference trajectories for the unicycle model.

### Running Controllers
1. Navigate to the `Controllers` directory.
2. Open the desired MATLAB script or Simulink model:
3. Run simulations and visualize the unicycle's behavior.

### Presentations
- Access the `Presentation` folder for reports and slides summarizing the project's findings.

---

## References

1. MATLAB and Simulink Documentation.  

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> **Note:** This project is developed for academic purposes. Ensure thorough testing and validation in controlled environments before applying these controllers to real-world systems.
