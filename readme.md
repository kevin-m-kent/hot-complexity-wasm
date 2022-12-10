## WASM Package for Hot Complexity Simulation

Builds a WASM package from Rust code that implements the fire burn simulation from the [Highly Optimized Tolerance](https://authors.library.caltech.edu/1527/1/CARpre99.pdf) paper. 

This is primarily for use in an interactive dashboard built in Javascript (D3). With this approach we are leveraging the speed of the Rust simulation in the context of the frontend visualization capabilities of Javascript.