# RoboStack (for ROS Iron)

Note:  ROS Iron is experimental. [ROS Humble](https://github.com/RoboStack/ros-humble) is recommended for most users at this time.

[![Conda](https://img.shields.io/conda/dn/robostack-iron/ros-iron-desktop?style=flat-square)](https://anaconda.org/robostack/)
[![Gitter](https://img.shields.io/gitter/room/RoboStack/Lobby?style=flat-square)](https://gitter.im/RoboStack/Lobby)
[![GitHub Repo stars](https://img.shields.io/github/stars/ihuicatl/ros-iron?style=flat-square)](https://github.com/ihuicatl/ros-iron/)
[![QUT Centre for Robotics](https://img.shields.io/badge/collection-QUT%20Robotics-%23043d71?style=flat-square)](https://qcr.github.io/)

[![Platforms](https://img.shields.io/badge/platforms-linux%20%7C%20win%20%7C%20macos%20%7C%20macos_arm64%20%7C%20linux_aarch64-green.svg?style=flat-square)](https://github.com/ihuicatl/ros-iron)
[![Azure DevOps builds (branch)](https://img.shields.io/github/actions/workflow/status/ihuicatl/ros-iron/linux.yml?branch=buildbranch_linux&label=build%20linux&style=flat-square)](https://github.com/ihuicatl/ros-iron/actions/workflows/linux.yml)
[![Azure DevOps builds (branch)](https://img.shields.io/github/actions/workflow/status/ihuicatl/ros-iron/win.yml?branch=buildbranch_win&label=build%20win&style=flat-square)](https://github.com/ihuicatl/ros-iron/actions/workflows/win.yml)
[![Azure DevOps builds (branch)](https://img.shields.io/github/actions/workflow/status/ihuicatl/ros-iron/osx.yml?branch=buildbranch_osx&label=build%20osx&style=flat-square)](https://github.com/ihuicatl/ros-iron/actions/workflows/osx.yml)
[![Azure DevOps builds (branch)](https://img.shields.io/github/actions/workflow/status/ihuicatl/ros-iron/osx_arm64.yml?branch=buildbranch_osx_arm64&label=build%20osx-arm64&style=flat-square)](https://github.com/ihuicatl/ros-iron/actions/workflows/osx_arm64.yml)
[![Azure DevOps builds (branch)](https://img.shields.io/github/actions/workflow/status/ihuicatl/ros-iron/build_linux_aarch64.yml?branch=buildbranch_linux_aarch64&label=build%20aarch64&style=flat-square)](https://github.com/ihuicatl/ros-iron/actions/workflows/build_linux_aarch64.yml)

[![GitHub issues](https://img.shields.io/github/issues-raw/ihuicatl/ros-iron?style=flat-square)](https://github.com/ihuicatl/ros-iron/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/ihuicatl/ros-iron?style=flat-square)](https://github.com/ihuicatl/ros-iron/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/ihuicatl/ros-iron?style=flat-square)](https://github.com/ihuicatl/ros-iron/pulls)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed-raw/ihuicatl/ros-iron?style=flat-square)](https://github.com/ihuicatl/ros-iron/pulls?q=is%3Apr+is%3Aclosed)

<!-- [__Table with all available packages & architectures__](https://robostack.github.io/iron.html) -->

## Why ROS and Conda?
Welcome to RoboStack, which tightly couples ROS with Conda, a cross-platform, language-agnostic package manager. We provide ROS binaries for Linux, macOS, Windows and ARM (Linux). Installing other recent packages via conda-forge side-by-side works easily, e.g. you can install TensorFlow/PyTorch in the same environment as ROS iron without any issues. As no system libraries are used, you can also easily install ROS iron on any recent Linux Distribution - including older versions of Ubuntu. As the packages are pre-built, it saves you from compiling from source, which is especially helpful on macOS and Windows. No root access is required, all packages live in your home directory. We have recently written up a [paper](https://arxiv.org/abs/2104.12910) and [blog post](https://medium.com/robostack/cross-platform-conda-packages-for-ros-fa1974fd1de3) with more information.

## Attribution
If you use RoboStack in your academic work, please refer to the following paper:
```bibtex
@article{FischerRAM2021,
    title={A RoboStack Tutorial: Using the Robot Operating System Alongside the Conda and Jupyter Data Science Ecosystems},
    author={Tobias Fischer and Wolf Vollprecht and Silvio Traversaro and Sean Yen and Carlos Herrero and Michael Milford},
    journal={IEEE Robotics and Automation Magazine},
    year={2021},
    doi={10.1109/MRA.2021.3128367},
}
```

## Installation, FAQ, and Contributing Instructions
Please see our instructions [here](https://robostack.github.io/GettingStarted.html).
