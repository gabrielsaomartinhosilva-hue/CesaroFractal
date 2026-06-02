# Automated Design and Miniaturization of Cesàro Fractal-Based RF Resonators for Chipless RFID Tags

## Submission ID: 10722

This repository contains the source code used in the article:

**"Automated Design and Miniaturization of Cesàro Fractal-Based RF Resonators for Chipless RFID Tags"**

The repository includes the algorithms responsible for generating Cesàro fractal geometries, used throughout the study.

## Repository Structure

```text
├── scripts/
│ ├── cesaro_generator.py
│ ├── geometry_functions.py
│ └── hfss_automation.py
│
├── examples/
│ ├── first_order/
│ └── second_order/
│
├── figures/
│ └── article_figures/
│
└── README.md

```

---

## Project Parameters

The main parameters used by the generator are:

| Parameter | Description |

|------------|-------------| | Perimeter | Total perimeter of the resonator |

| Angle | Cesaro indentation angle (degrees) |

| Order | Fractal iteration order |

| Segment Width | Width of the conductive tracks |

| Distance | Coupling distance between the resonator and the feed line |

---

## Reproducing the Results

1. Open Ansys HFSS.

2. Configure the Python environment.

3. Run the geometry generation script.

4. Select the desired:

- Fractal order

- Perimeter

- Angle

5. Generate the model.

6. Run the electromagnetic simulation.

7. Extract the S parameters and compare them with the results presented in the article.

---

## Experimental Validation

The resonators presented in this article were fabricated on FR4 substrates and validated through measurements with a Vector Network Analyzer (VNA).

The prototypes evaluated include:

- Square Loop Resonator (0°)
- First-Order Caesar Resonator (45°)
- First-Order Caesar Resonator (60°)
- Second-Order Caesar Resonator (60°)

The measured results showed good agreement with the responses simulated by HFSS.

--

## Summary of Results

The proposed methodology demonstrated:

- Up to 20% reduction in the resonator base dimension compared to a conventional square loop resonator.

- Fine-tuning of the resonance frequency through angular variation.

- Automated generation of higher-order fractal geometries.

- Good agreement between simulation and experimental measurements.

- ---

## Citation

If you use this code in your research, please cite:

```bibtex
@article{Silva2026Cesaro,

author={Gabriel Sao Martinho Da Silva and Rodrigo Luiz Ximenes and Lisandro Manuel De la Torre Rodriguez and Leonardo Lorenzo Bravo Roger},

title={Automated Design and Miniaturization of RF Resonators Based on the Cesaro Fractal for Chipless RFID Tags},

journal={IEEE},

year={2026}

}

```

---

## License

This project is provided for academic and research purposes.

## ✉️ Contact

For any questions related to the article, please contact us.
```
gabriel.saomartinho.silva@gmail.com
``
