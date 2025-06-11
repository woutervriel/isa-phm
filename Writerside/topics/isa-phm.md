# ISA for PHM

## Introduction

The original ISA model was developed to capture metadata for the field of life, environmental and biomedical sciences such as toxicology and plant sciences.

Terms and definitions common in these fields are not common in the field of PHM. Hence, a model extension was made that provided clearer definitions for the PHM community.

The ISA model extension for PHM is called the **ISA-PHM** model. It is a community-driven extension of the ISA standard, and it is coordinated by a working group.

The ISA-PHM model is built upon the original ISA model, and it extends the original model with terms and definitions that are relevant for the field of PHM. The ISA-PHM model is designed to capture metadata for predictive maintenance projects, including information about the assets, sensors, data collection processes, and maintenance actions.


## A short introduction to PHM

PHM stands for Prognostics and Health Monitoring. It is a field that focuses on improving the reliability and availability of systems through data-driven diagnostic and prognostic algorithms. These algorithms are trained on historical data to detect and predict future failures, thereby enhancing maintenance strategies. The data for these algorithms is often collected from sensors in testing / lab environments, where components in a test setup are monitored during a test, for example spinning a bearing.

For PHM purposes, two types of experiments can be considered:
1. **Diagnostic**: a specific (combination of) fault(s) is introduced (or observed) in a test piece, and the associated response is measured.
2. **Degradation**: a test piece undergoes (either constant or time-varying) loading for a prolongued period, preferably until failure, while it’s (evolution of) response is measured.

Each of these can be based on:
- Numerical simulations: loading and conditions can be fully controlled, #sensors may be infinite, inclusion of failures is relatively easy, typically not very realistic, no noise / interference.
- Lab experiments: loading and conditions can be fully controlled, #sensors depends on hardware, inclusion of (run-to-)failures is challenging, behavior rather realistic, typically low noise / interference.
- Extraction from operational systems: both encountered faults and loading / conditions are given (uncontrolled), #sensors depends on hardware, inclusion of failures is almost impossible, very realistic, typically high noise / interference.


## Translation ISA to the PHM context


