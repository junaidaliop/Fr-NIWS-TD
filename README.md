# Fr-NIWS-TD

Data repository for the paper:

> **A novel design of time delay fractional nonlinear SIHQR worm transmission model for Industrial IoT networks: Machine learning knowledge driven neuroarchitecture analysis**
>
> *Submitted to Chaos, Solitons & Fractals*

## Data

The `Data/` folder contains numerical solutions and NM-ARXN-LM neural network results for the fractional-order SIHQR worm propagation model across **5 case studies × 5 fractional orders** (ξ = 1.0, 0.9, 0.8, 0.7, 0.6):

| Subfolder | Contents |
|:----------|:---------|
| `numerical_data/` | Reference solutions from the FDE solver along with time domain (input) |
| `neural_network_predictions/` | NM-ARXN-LM predicted time series and pointwise errors |
| `trained_neural_network_module/` | Trained NARX network objects and training records |

Files follow the naming convention: `*_CS{1-5}_xi_{order}.mat`

## License

[MIT](LICENSE)
