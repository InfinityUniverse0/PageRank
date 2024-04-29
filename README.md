# PageRank

PageRank Algorithm

## Features

- In **addition** to Basic PageRank Algorithm (Basic Update Algorithm), some measures are taken for **Memory Optimization**

  - Using **sparse matrix** encoding

  - Using **Block-Stripe Update Algorithm**

- Support **Command Line Args** to control related args manually

- 🎉 Multi-Platform
  - Linux :penguin:, MacOS :apple: and Windows :checkered_flag: .


## Quick Start

**Prerequisite**: Please make sure that you have installed `CMake` on your machine. If not, you need to install `CMake` first.

When you are in the same directory with this `README` file, run the below command in your terminal (bash, zsh, command line, or powershell):

```sh
cmake . -B build
cmake --build build
```

Or using **Release** Mode:

```sh
cmake . -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build --config Release
```

Then, run the below command to execute the PageRank program:

```sh
./PageRank
```

> [!WARNING]
>
> **WARNING:** Although the default directory of `PageRank` is in the same directory with `CMakeLists.txt` , that depends on your build system.

### DataSet

You need to put your dataset file in the same dir with the generated executable file `PageRank` , and rename it as `Data.txt` .

The format of the lines in the file is as follow:

```
FromNodeID ToNodeID
```

> [!NOTE]
>
> **NOTE:** Node ID starts from `1` .

The result is saved in `.txt` . Each line contains:

```
NodeID Score
```
