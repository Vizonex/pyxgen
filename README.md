# pyxgen
A Cython Bindings Generator Written with Python. Inspired by many different projects.

# Why A new bindings generator?
To be fair I didn't want to have to do all the work myself but time and time again 
I have been proven wrong. There should be an updated and easy way to generate both
header externs and cdef extension classes without having to do very much. 
Most of the time developers spend in cython is consumed by needing to bind C/C++ libraries alike, 
by making a tool that can generate all of that the time spent can be cut off significantly.
If rust-bindgen could do it so could we. 

In the future My plan is to use this library to create a brand new Cython Generated 
Version of libclang that we can use to further enhance this project. 

The Project's goal is to remain AI-Free. Based on the principle that Teaching yourself 
how to do something will allow you to learn something.


## Credits
- [pxdgen](https://github.com/earowley/pxdgen) inspired me to further Continue the concept into also brought up the idea that we should add parameter names.
- [rust-bindgen](https://github.com/rust-lang/rust-bindgen) brought up the idea of having an organized setup & compile api.
- cython-wrapper Inspired this project as a whole although it's an older project.

