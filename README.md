# GPU-Accelerated Deep Learning for Time Series

![Saturn Cloud GPU Multi-Forecast](saturn_cloud_gpu_multiforecast.jpg)

This is a short demonstration of __GPU-Accelerated Deep Learning for Time Series__ that was part of the presentation, _"The Future of Time Series | Rise of the High-Performance Forecasting System"_. Video and all supporting contents are provided as part of [Learning Labs PRO, Lab 53](https://university.business-science.io/p/learning-labs-pro).

## Modeltime GluonTS

This presentation showcases `modeltime.gluonts` (an R package used for deep learning forecasting with GluonTS as a forecasting backend). The [Modeltime GluonTS Documentation](https://business-science.github.io/modeltime.gluonts/) can be found here. Modeltime GluonTS is part of the [Modeltime Ecosystem](https://business-science.github.io/modeltime/), a series of R Packages that provide scalable forecasting workflow and infrastructure. 

## Saturn Cloud | NVIDIA GPU Workspace

![GPU Workspace]()

- We leveraged the [SaturnCloud Platform](https://www.saturncloud.io/) to create a GPU Workspace and Modeltime GluonTS Environment 
- The environment uses MXNET CUDA Backend enabling GluonTS to leverage GPUs and greatly speed-up training
- The result is training times 2X to 5X faster than on a 12-Core Laptop


