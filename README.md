# Peugeot 2008

This repository contains signal set configurations for the Peugeot 208, organized by model year and version. The files are structured with a **default.json** baseline, which serves as the primary configuration for most model years, with additional files for model-specific overrides where necessary.

## About the Peugeot 208

The Peugeot 208 is a popular supermini car produced by the French automaker Peugeot, known for its compact size, efficient performance, and modern features. Launched in 2012, the Peugeot 208 is now in its second generation, with each generation introducing significant updates in design, technology, and performance.

- **Phase I, First Generation (2012-2019)**: The original Peugeot 208 replaced the 207 and was designed with a more compact, aerodynamic look while retaining interior space. It was offered with a range of petrol and diesel engines and became well-known for its efficient performance and stylish design. Over the years, it received incremental updates, including new tech features and refinements to the engine lineup.

- **Phase II, Second Generation (2019-present)**: The second-generation Peugeot 208 debuted in 2019 and adopted Peugeot’s new design language, featuring a bold grille, full LED lighting, and a more robust, sporty look. It introduced the fully electric **e-208** model, alongside traditional petrol and diesel options, reflecting Peugeot’s push towards electrification. The interior features Peugeot’s latest i-Cockpit design, with a digital instrument cluster, touchscreen interface, and advanced safety features.

## Repository Structure

The directory is organized as follows:
```plaintext
signalsets/
  └── v3/
      ├── default.json        # Default configuration (applies to Phase 2 and future models)
      └── 2012-2019.json      # Override configuration for first-generation models (Phase 1, 2012-2019)
```
- **default.json**: Serves as the primary configuration, covering models from 2019 onwards (second generation), including the electric e-208. This file acts as the fallback configuration for all model years unless an override file specifies otherwise.

- **2012-2019.json**: Override configuration specifically for first-generation models, allowing them to be distinct from the baseline configuration in `default.json`.

If a new configuration is needed in the future (e.g., for model years 2027 and beyond), a new JSON file (e.g., `2019-2026.json`) can be created to lock in the 2019-2026 configuration, allowing `default.json` to reflect the latest specifications.

## Usage

Each JSON file in the `v3/` directory corresponds to a specific model year range, with `default.json` providing the primary configuration. Override files, such as `2012-2019.json`, handle unique cases for specific model years or generations.

## Contributing

Contributions are welcome! If you would like to add support for additional model years or specific configurations, please open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch for your changes
3. Commit your changes and open a pull request with a detailed description

## Issues

If you encounter any issues or would like to discuss improvements, please feel free to open an issue. We encourage collaboration and appreciate feedback to make the repository as accurate and useful as possible.