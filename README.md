# Stoke-based-Representation-Learning-with-GANs

### Abstract:
Human visual system has evolved with lots of complexity and robustness. As
artificial visual systems are now available to be deployed in the fields, there are
some issues which can hurdle this progress. To understand further, the benchmark
visual models show poor results when confronted with out-of-distribution image data
which can be either spatially transformed or rotationally transformed. On the
contrary, our visual systems don’t work in such ways, for example, if someone gives
me an image of number 3 rotated 30”, we can still detect 3, but our best recognition
models fail to do so. In order to overcome this issue, one approach learns the graph
made up of the strokes of the image data, which as the graph structure would
preserve the connections between nodes, would allow spatial and rotation invariant
models to emerge. Following similar direction, our project group explores, the
normalised Fourier transforms to yield affine transformation invariant representations
of the sketch strokes and used the GNN model to learn these graph structures. Our
work shows successful results and provides a good direction to extend the work in
the future.

### Visit implementation [Fourier Descriptors](https://colab.research.google.com/drive/1-OzR4dc4RXJ0QxnIhnOeh9gSHcli9zUl?usp=share_link).
### [With GNN ](https://colab.research.google.com/drive/1kllD1luRDxY01sxEcItL8d8n20CGbO02?usp=share_link)

### To access full report, [Click here](https://github.com/pathu007/Stoke-based-Representation-Learning-with-GANs/blob/main/Final%20Report%20-%20Stroke-Based%20Representation%20Learning.pdf)

### References:
[1] Cheng, S. (2021) SSR-GNNs: Stroke-Based Sketch Representation with Graph Neural
Networks. (Preprint)
[2] Kuhl, F.P. & Giardina, C.R. (1982) Elliptic Fourier Features of a Closed Contour. Computer
Graphics and Image Processing, Vol 18, Issue 3, pp. 236-258. ISSN 0146-664X,
https://doi.org/10.1016/0146-664X(82)90034-X.
[3] Engstrom, L., Tran, B., Tsipras, D., Schmidt, L., Madry, A. (2019) Exploring the Landscape of
Spatial Robustness. International Conference on Machine Learning. pp. 1802–1811
[4] Blidh, H. Pyefd. https://github.com/hbldh/pyefd.
