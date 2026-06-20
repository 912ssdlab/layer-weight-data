# Layer Deadline-aware Refresh Scheduling for 3D NAND SSDs to Minimize I/O Interference

## 1. Introduction

We provide the layer weight factor (w(l)) values used in our paper. These values characterize the reliability variations among different physical layers in 3D NAND flash memory.

## 2. Measurement

The data were obtained from physical measurements on 12 commercial Samsung TLC 3D NAND flash chips. The layer weight factor is calculated as the ratio of the measured RBER of each physical layer to the average RBER of its block.

## 3. Data

samsung_layer_weight.xlsx contains the layer weight values under different P/E cycle and retention time conditions, including 1 and 1,500 P/E cycles and retention times of 0, 6, 12, and 18 hours.

## 4. Usage

The provided layer weight values can be used to estimate layer-level RBER and calculate layer-specific retention deadlines for layer-aware refresh scheduling.
