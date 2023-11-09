# LC-ASC
Here we present the Level-Crossing Analog-to-Spike Converter (LC-ASC) VerilogA models. The LC-ASC uses level-crossing sampling, to achieve low-power compressive sampling for neuromorphic biomedical systems.

The following two figures show the illustration of LC-ASC modeling and evaluation process. VerilogA implementation of LC-ASC consists of 3 modules: signal folding circuit, comparator, and control logic. Performance calculation modules include zero-order reconstruction and counters for compression ratio calculation.

<div align=center>
<img width="550" alt="1681781259924" src="https://user-images.githubusercontent.com/50477524/232645153-63638479-ac16-4c92-9e7e-56fd5f7d1a0b.png">
</div>
<div align=center>
Fig. 1. Illustration of LC-ASC modeling and evaluation process.
</div>
<div align=center>
<img width="492" alt="1681781259924" src="https://user-images.githubusercontent.com/50477524/232645641-03228c7b-1fa1-4633-b613-c7ab3c9882a8.png">
</div>
<div align=center>
Fig. 2. System architecture of the LC-ASC model.
</div>
