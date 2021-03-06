# rayml

![Example rendered scene](examples/demo.jpg)

A raytracer written in OCaml. It supports diffuse("matte") and
reflective("metallic") surfaces.

The design of the software roughly follows Peter Shirley's mini-book
series [Raytracing in One Weekend][weekend] which presents a raytracer
in C++. I've adopted the programming style to suit OCaml's functional
style.

## Usage

You need to have OCaml installed. Running `make display` will compile
the program and renders the hard-coded scene displayed above.

[weekend]: http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html
