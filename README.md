This repository contains the experiments, visualizations, and analysis I conducted while AUDITING MAT1510: Deep Learning — Theory & Data Science.
The goal of this project is to connect core theoretical principles from the course with empirical behavior observed in modern neural networks.

The experiments explore:
The Mutual Information Plane, showing that modern networks exhibit compression. 
Not all learned features are one-dimensionally linear paper showing that features like days of the week are in fact not linear, and form a circular shape in line with the toy model of superposition blog post. 
Representation geometry and clustering in large-scale vision models such as DINOv2, where patching occurs around the features of the object. 
Attention head dynamics in transformer models, including clustering behavior around specific tokens where tokens can be considered to be particles on a unit sphere. Unit sphere understanding comes from the layernorm, where we divide by the L2 norm/variance. 
