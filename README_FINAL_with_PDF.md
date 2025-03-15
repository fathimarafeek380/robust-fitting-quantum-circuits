# Robust Fitting in Gate-Based Quantum Computers

## Description
This project demonstrates robust fitting and error mitigation in noisy gate-based quantum circuits using Qiskit. The aim is to simulate the impact of quantum noise and apply basic error mitigation techniques to improve the accuracy of quantum state measurements. The project is part of research and learning in the domain of NISQ-era quantum computing.

## Features
- Designed a 2-qubit quantum circuit using Hadamard and CNOT gates
- Simulated depolarizing noise using Qiskit's AER simulator
- Applied error mitigation by rescaling output probabilities
- Visualized noisy vs mitigated results using bar charts

## Technologies Used
- Python
- Qiskit
- NumPy
- Matplotlib

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/gowthammarella/robust-fitting-quantum-circuits.git
   ```
2. Navigate into the project folder:
   ```
   cd robust-fitting-quantum-circuits
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
Run the main script to execute the quantum circuit, simulate noise, apply mitigation, and plot the results:
```
python robust_fitting_quantum.py
```

## Output
The output consists of a comparison between noisy and mitigated quantum measurement results in a bar chart:
```
![Noisy vs Mitigated Results](images/results_plot.png)
```

## Folder Structure
```
robust-fitting-quantum-circuits/
│
├── robust_fitting_quantum.py
├── README.md
├── requirements.txt
├── LICENSE
├── Quantum_Error_Mitigation_Techniques_Detailed.pdf
└── /images
    └── results_plot.png
```

## Additional Reading
For a deeper understanding of advanced quantum error mitigation techniques such as QEC, ZNE, and Machine Learning-based mitigation, refer to the following resource:
[Quantum Error Mitigation Techniques – Detailed PDF](Quantum_Error_Mitigation_Techniques_Detailed.pdf)

## Author
Gowtham Royal Vikramadithya

## License
This project is licensed under the MIT License – see the LICENSE file for details.

## Contributions
Feel free to fork this repo, submit pull requests, or share your ideas for improving quantum error mitigation techniques.
