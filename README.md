# Hospital System Project

## Overview

This project is a Hospital System implemented in C++ programming language. The system is designed to manage patients within a hospital with various specializations. 

## Project Description

The Hospital System manages patients for different specializations within a hospital. It supports the following functionalities:
- **20 Different Specializations**: The hospital has 20 specializations (e.g., Children, Surgery, etc.).
- **Queue Management**: Each specialization has a queue with a maximum of 5 available spots.

### Features

1. **Adding a Patient**
   - **Input**: The system reads the requested specialization (1-20), the patient's name, and status (0 = regular, 1 = urgent).
   - **Condition**: If 5 patients already exist, the system apologizes and doesn't accept the patient.
   - **Queue Handling**: 
     - Regular patients are added to the end of the queue.
     - Urgent patients are added to the beginning of the queue.

2. **Printing Patients**
   - The system prints the patients for the specializations that have waiting patients.

3. **Doctor Picking Up a Patient**
   - **Input**: The system reads the requested specialization.
   - **Condition**: If no patients are available, the doctor is informed.
   - **Action**: If patients are available, the patient is asked to go with the doctor and is removed from the queue.

## Usage

To use this project, compile and run the provided C++ code. Follow the prompts to add patients, print the list of waiting patients, and handle doctor pick-ups.

## Inspirational Quotes

- “Acquire knowledge and impart it to the people.”
- “Seek knowledge from the Cradle to the Grave.”

## Acknowledgments

- Special thanks to Mostafa S. Ibrahim for his guidance and project inspiration.
---

Feel free to contribute to this project by forking the repository and submitting pull requests. For any issues or suggestions, please open an issue in the GitHub repository.
