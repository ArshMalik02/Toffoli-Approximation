# Toffoli Approximation

This project involves approximating the Toffoli gate using five 2-qubit gates. The optimization process is carried out using the QGOpt optimizer to achieve a precise approximation. 

## Methodology

To approximate the Toffoli gate, the following steps were taken:

1. **Initialization**: Five 2-qubit matrices were initialized.
2. **Target Definition**: The Toffoli gate was defined as the target for the optimization.
3. **Optimization**: The QGOpt optimizer was run for 500 iterations to minimize the Hilbert-Schmidt distance between the target gate and the approximation.

## Results

The optimization process yielded the following results:

- **Minimum Hilbert-Schmidt Distance**: 0.3826834323650892
- **Optimization Process**: The optimization loop was visualized, showing the error versus iteration plot, which helped in analyzing the convergence of the optimizer.

## Code References

- The optimizer used for this project is QGOpt. More information can be found in the [QGOpt documentation](https://qgopt.readthedocs.io/en/latest/quick_start.html).

## Visualizations

- **Target Gate**: The Toffoli gate was set as the target for the optimization.
- **Initialization**: Five 2-qubit unitaries were initialized.
- **Optimization Loop**: The loop ran for 500 iterations, and the error versus iteration plot was generated.
- **Results**: The minimum Hilbert-Schmidt distance was recorded, and the optimization results were visualized.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- QGOpt

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ArshMalik02/toffoli-approximation.git
    cd toffoli-approximation
    ```

2. Install the required packages:
    ```bash
    pip install qgopt
    ```

3. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open the `approx_toffoli.ipynb` notebook from the Jupyter interface.

## Usage

Run the cells in the `approx_toffoli.ipynb` notebook to see the implementation and results of the Toffoli gate approximation.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Special thanks to the developers of QGOpt for providing a robust optimization tool.
