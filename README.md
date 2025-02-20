# ⚛️ `Quantum Grover's Algorithm` Qiskit Runtime Demo ⚛︎

This notebook demonstrates how to implement Grover's algorithm using Qiskit Runtime. Grover's algorithm is a quantum algorithm that can be used to search an unsorted database with N entries in O(√N) time.

[➡️ NOTEBOOK ⚛️]()

## Requirements

- Qiskit
- Qiskit IBM Runtime
- IBM Quantum API token

## Usage

1. Install the required packages:
```bash
pip install qiskit qiskit-ibm-runtime
```

2. Save your IBM Quantum API token to the `IBM_QC_API` environment variable.
3. Run the notebook cells in order.

## Steps

1. **Map classical inputs to a quantum problem:** Define the oracle function that marks the target states.
2. **Optimize problem for quantum execution:** Use the Qiskit transpiler to optimize the circuit for the target backend.
3. **Execute using Qiskit Primitives:** Use the `Sampler` primitive to execute the circuit on a quantum computer or simulator.
4. **Post-process, return result in classical format:** Analyze the results and plot the distribution of the measured states.

## Results

The notebook outputs a distribution plot showing the probability of measuring each state. The marked states should have a higher probability than the other states.

## Conclusion

This notebook demonstrates how to use Qiskit Runtime to implement Grover's algorithm. This algorithm can be used to solve a variety of search problems.

## Author

[0xZee]

## License

[License]
