# neopz-nedelec-el
This is a repository containing documents regarding the implementation of the Nédélec element of the first kind in the NeoPZ framework(https://github.com/labmec/neopz). Since of the experimental status of the implementation, it is available in a branch called `hcurl-tests-and-experimentations`.

The implementation was possible thanks to the [deal.II report](http://www.dealii.org/reports/nedelec/nedelec.pdf) on their implementation of the Nédélec elements. However, the approach taken in [NeoPZ](https://github.com/labmec/neopz) is different once the lower order functions are used in higher order elements, aiming for an easy employment of hp-adaptivity techniques (hopefully it will work!).

I will soon be posting a technical report, but at the present time I can only provide the *Mathematica notebook* that I used for generating the functions present in `${PROJECT_SOURCE_DIR}/Mesh/TPZHCurlNedFTriElShape.cpp`.
### NOTICE
This is part of my MSc project. I cannot be sure there are no mistakes in this code. In case any are found, I would most appreciate if they could be reported. Feel free to contact me.