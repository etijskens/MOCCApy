# Python package MOCCApy

## A Python-first implementation of the MOCCA project

I have been practising Python-first approach for many years now in the field of scientific computing.

Advantages:

- Python's learning curve is far less steep than that of C++ or Modern Fortran.
- Many high quality Python modules available with excellent performance. 
- multi-core and multi-process approaches possible
- can be augmented with low-level C++ code where necessary (that is in fact what all HPC Python modules do)

So it is not a performance bottleneck.

Also interesting would be to develop a Julia-first version along with it and look at performance.

Hephaestos is a complicated monster and not well designed (there is a different preprocessor for each src_orig file).

**Discussion on `Hephaestos`**. Apperently, it generates code that 
- accounts for the symmetry of the problem
- generates the potential models, some potentials depend on the symmetry of the problem. E.g. if the problem has time reversal symmetry, there can be no currents, and corresponding potential contributions necessarily vanish. 

So, there is a (small) coupling between the symmetry part and the model part.  
