==============
Onnx runtime windows ARM python packages
==============

This repo contains onnxruntime pip install packages for windows ARM. The wheels are build using different Execution providers
1. Onnxruntime: Default onnxruntime to target the CPU
2. Onnxruntime-directml <https://onnxruntime.ai/docs/execution-providers/DirectML-ExecutionProvider.html>
3. Onnxruntime-qnn <https://onnxruntime.ai/docs/execution-providers/QNN-ExecutionProvider.html>

Onnx provides a script to build for different EP: <https://onnxruntime.ai/docs/build/eps.html>
You can use these packages to easily get started with working with onnxruntime on windows ARM

Installation
============
1. Onnxrutime: Target the CPU only
```
pip install https://github.com/mwangistan/Onnxruntime-windows-ARM-wheels/raw/main/onnxruntime-1.15.1-cp311-cp311-win_arm64.whl
```
2. Onnxruntime-directml: Target the GPU using Directml
```
pip install https://github.com/mwangistan/Onnxruntime-windows-ARM-wheels/raw/main/onnxruntime_directml-1.15.1-cp311-cp311-win_arm64.whl
```
3. Onnxruntime-qnn: Target the NPU using Qualcomm AI Engine SDK
```
pip install https://github.com/mwangistan/Onnxruntime-windows-ARM-wheels/raw/main/onnxruntime_qnn-1.15.1-cp311-cp311-win_arm64.whl
```
