# OPSN

## Intro

这个项目是一个用于 [项目功能描述，例如：2D 雷达 SLAM 算法] 的实现，旨在通过 [简要介绍该项目的目的，例如：实现机器人自主导航、环境建图和定位]。

## Features

- **Input Handling**: Normalizes input data containing features such as position and velocity.
- **Path Calculation**: Computes path positions from starting to ending points, incorporating multiple control points.
- **Threat Detection**: Evaluates threat levels based on distances to circular threat objects.
- **Path Optimization**: Aggregates threat data to determine the safest and most efficient path.
- **Output Generation**: Provides the weighted path length for further decision-making processes.

## Installation

To install the required dependencies, you can use pip:

```bash
pip install -r requirements.txt
