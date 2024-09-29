# Material-Simulation
This material simulation project is part of the B. Tech Project Titled "Recrystallization Modelling using Monte Carlo Method"

Recrystallization can be defined as the formation of a new grain structure in a plastically deformed material. This recrystallization occurs through the formation and migration of high-angle boundaries. As plastic deformation increases, the material becomes thermodynamically unstable and this leads to recrystallization wherein new grains of relatively low stored energy are nucleated in the microstructure. By consuming the high-energy grains in their surroundings, these newly nucleated grains reduce the internally stored energy within the material, thereby increasing its thermodynamic stability.


In the below video, we see a 3D Material with 5x5x5 structure, recrystallizing to reduce its internal energy and leading to grain growth (Each grain orientation, is shown by a different colour)




https://github.com/user-attachments/assets/fae8b785-de01-4e25-9672-06dc9264e188


These results from our python code implementation of the paper titled "Three-Dimensional Monte Carlo Simulation of Recrystallization in Silver" DOI 10.1109/BCGIn.2011.110

The Simulation was done for 100 Monte Carlo steps, on 10*10*10 highly strained simulated silver metal, as described in the paper. We have added the additional logic of considering the minimum grain orientation angle, from the 24 symmetric rotational operations in the cubic system, as described by Kocks et. al. (Kocks, Fred & Tomé, Carlos & Wenk, H-R. (2000). Texture and Anisotropy. Preferred Orientations in Polycrystals and Their Effect on Material Properties Book).

Outputs shown below

Initial State, Randomly oriented grains (Representing a Highly Stressed material)

![10x10x10_5deg_iter=1](https://github.com/user-attachments/assets/afa35277-91a5-4c5b-8e87-039fd6b60dc8)

After 5 Iterations

![10x10x10_5deg_iter=5](https://github.com/user-attachments/assets/6fbef7e5-5de7-4678-9cd3-02eef3dc5a55)

After 10 Iterations

![Figure 1](https://github.com/user-attachments/assets/b72decdf-f9e4-45f3-82bb-1beb0ba82a2b)

After 50 Iterations

![Figure 1 (3)](https://github.com/user-attachments/assets/eface0d1-4f9b-49fd-a0b8-89941e479f3b)

After 100 Iterations

![Figure 1 (6)](https://github.com/user-attachments/assets/e37ccc4b-c53a-475d-9aa8-633d75a6eee5)


