This is the summary of the paper of the pytorch framework.

- Pytorch gives both speed and usability.
- It provides an imperative and Pythonic programming style that supports code as a model, makes debugging easy and is consistent with other popular scientific computing libraries, while remaining efficient and supporting hardware accelerators such as GPUs.
- It performs immediate execution of dynamic tensor computations with automatic differentiation and
GPU acceleration, and does so while maintaining performance comparable to the fastest current
libraries for deep learning.

###### Four Major trends in scientific computing imp for deep learning:

1. The development of domain specific languages such as APL, MATLAB, R and Julia, turned multidimensional arrays (often referred to as tensors) into first-class objects supported by a comprehensive set of mathematical primitives (or operators) to manipulate them. Separately, libraries such as NumPy, Torch, Eigen and Lush made array-based programming productive in general purpose languages such as Python, Lisp, C++ and Lua.

2. The development of automatic differentiation made it possible to fully automate the daunting labor of computing derivatives. This made it significantly easier to experiment with different machine learning approaches while still allowing for efficient gradient based optimization. The autograd package popularized the use of this technique for NumPy arrays, and similar approaches are used in frameworks such as Chainer, DyNet, Lush, Torch, Jax and Flux.jl.

3. Third, with the advent of the free software movement, the scientific community moved away from closed proprietary software such as Matlab, and towards the open-source Python ecosystem with packages like NumPy, SciPy, and Pandas. This fulfilled most of the numerical analysis needs of researchers while allowing them to take advantage of a vast repository of libraries
to handle dataset preprocessing, statistical analysis, plotting, and more. Moreover, the openness, interoperability, and flexibility of free software fostered the development of vibrant communities that could quickly address new or changing needs by extending the existing functionality of a library or if needed by developing and releasing brand new ones.

4. Finally, the availability and commoditization of general-purpose massively parallel hardware such as GPUs provided the computing power required by deep learning methods. Specialized libraries such as cuDNN, produced a set of high-performance reusable deep learning kernels that enabled frameworks such as Caffe, Torch7, or TensorFlow to take advantage of these hardware accelerators.

###### Pytorch Design principles.

1. Be Pythonic. 
2. Put researchers first.
3. Provide pragmatic performance.
4. Worse is better.

###### Usability Centric Design.

1. Deep learning models are just Python programs
2. Interoperability and extensibility
3. Automatic differentiation


###### Performance focussed implementation.

1. An efficient C++ core.
2. Separate control and data flow.
3. Custom caching tensor allocator.
4. Multiprocessing.
5. Reference counting.

###### Evaluation.

1. Asynchronous dataflow.
2. Memory management.
3. Benchmarks.
4. Adoption.

###### Conclusion and Future Work.

- we plan to continue to improve the speed and scalability of PyTorch. 
- Most notably, we are working on the PyTorch JIT: a suite of tools that allow PyTorch programs to be executed outside of the Python interpreter where they can be further optimized. 
- We also intend to improve support for distributed computation by providing efficient primitives for data parallelism as well as a Pythonic library for model parallelism based around remote procedure calls.
