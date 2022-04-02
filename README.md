# Maya Ascii Parser

Maya Ascii file (.ma) standalone parser, view essential file information
without needing to wait for Maya to open.

![preview](https://i.imgur.com/2SDq27G.png)

## Getting Started

1. Download and unzip the whole package


2. Launch the python file

    ```commandline
    python example.py
    ```
   
## Dependencies

- [Qt](https://github.com/mottosso/Qt.py): a module that supports different
python qt bindings (Only needed if you need UI support functionalities)
    ```
    pip install Qt.py
    ```

Already packaged dependencies with locked version of the following,
but you will need to clone using `git clone --recursive`

- [pipelineUtil](https://github.com/leixingyu/pipelineUtil)

## Speed Tests

[caching ascii data | creating dag nodes | total time]

### model-village-user-guide.ma 

> [6.95s | 6.91s | 13.86s]

- 9,134,983 lines
- 392,495,914 bytes
- 13,886 nodes

### PhoenixFD_BeachWaves.ma 

> [3.06s | <0.01s | 3.06s]

- 3,296,117 lines
- 209,392,366 bytes
- 115 nodes

### Kayla 2017 Rig.ma

> [2.16s | 0.07s | 2.23s]

- 2,128,357 lines
- 114,675,946 bytes
- 7,025 nodes
