GafferML-examples-YOLO
====

(assuming Linux, adapt for other plaform)

- Clone this repository

```
git clone https://github.com/lucienfostier/GafferML-examples.git
```

- Install Gaffer

You need a version of Gaffer that supports GafferML (at the time of writing https://github.com/GafferHQ/gaffer/actions/runs/12029799245/artifacts/2238512419)
See GafferHQ/Gaffer's github page for more details in installing Gaffer.

- Download ONNX-Runtime

Download the following link https://github.com/microsoft/onnxruntime/releases/download/v1.19.2/onnxruntime-linux-x64-1.19.2.tgz
and uncompress it using `tar -xvf`

- Start Gaffer

Set the `ONNX_ROOT` environment variable and start Gaffer
```
env ONNX_ROOT=~/onnxruntime-linux-x64-1.19.2 gaffer
```

- Load the script + reference

```
file>open...
```

Naviguate to the folder of examples

```
cd GafferML-examples/examples/YOLO
```

Load `YOLO.gfr`

![YOLO_examples](https://github.com/user-attachments/assets/9e4c160e-de0d-47a7-8ab7-623cf6bd86ab)


