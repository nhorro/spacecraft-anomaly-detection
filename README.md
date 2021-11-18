# spacecraft-anomaly-detection

This project contains experiments with algorithms to identify anomalies in multivariate series with a focus on spacecraft applications.

Each experiment is a jupyter notebook that generates one or more models to process multivariate series.

Dependencies are contained in a conda environemnt.

~~~bash
conda env create -f anomalies-env.yml
conda activate anomalies-env.yml
~~~

Project organization:

~~~
./
    data                 Contains data, or URIs to download.
    models               Trained models are exported here.
    notebooks            Experiments.
    README.md            This file.
    anomalies-env.yml    Conda environment for Python3/Jupyter.    
~~~

## References and useful links

General anomaly detection:

- [Deep Learning for Anomaly Detection: A Review](https://arxiv.org/pdf/2007.02500.pdf)
- [ADRepository: Real-world anomaly detection datasets](https://github.com/GuansongPang/ADRepository-Anomaly-detection-datasets)
- [Deep distance-based outlier detection (KDD18)](https://github.com/GuansongPang/deep-outlier-detection)
- [Unsupervised Representation Learning by Predicting Random Distances](https://github.com/billhhh/RDP/)
- [DevNet: An End-to-end Anomaly Score Learning Network](https://github.com/GuansongPang/deviation-network)
- [OCAN: One-Class Adversarial Nets for Fraud Detection](https://github.com/PanpanZheng/OCAN)
- [Anomaly Detection for Multivariate Time Series through Modeling Temporal Dependence of Stochastic Variables](https://github.com/NetManAIOps/OmniAnomaly)
- [Beginning Anomaly Detection Using Python-Based Deep Learning by Sridhar Alla and Suman Adari (Apress, 2019)](https://github.com/Apress/beginning-anomaly-detection-using-python-based-dl)

Aerospace spacecraft/satellite telemetry specific:

- [Satellite-Telemetry-Anomaly-Detection](https://github.com/sapols/Satellite-Telemetry-Anomaly-Detection)
- [ESA ACF - Anomaly Detection in Satellite Telemetry](https://www.esa.int/gsp/ACT/coffee/2020-09-11-%20AnomalyDetection/)
- [satellite-telemetry-project](https://jovian.ai/amgd2112/satellite-telemetry-project)
- [LASP Public lecture: Machine Learning at LASP](https://www.youtube.com/watch?v=1zj5Myp-afc)

Embedded bus (CAN, etc.) oriented:

- [CANBus Traffic Anomaly Detection with LSTM and Autoencoders](https://github.com/nhorro/can-anomaly-detection)