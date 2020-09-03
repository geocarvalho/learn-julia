# learn-julia
Some scripts from my path to learn Julia

# Reference courses:

* [Julia programming tutorial - codebasics](https://www.youtube.com/watch?v=cvnHHSK_O6E&list=PLeo1K3hjS3uvHr7N7j3GcMj48SdiTa_19&index=3)
* [Julia for data science, by Dr. Huda Nassar](https://www.youtube.com/watch?v=iG1dZBaxS-U&list=PLP8iPy9hna6QuDTt11Xxonnfal91JhqjO&index=2)
* [Julia data science basic full course - Abhishek Agarrwal](https://www.youtube.com/watch?v=lwj-1mclq0U&t=835s)
* [18.S191: Introduction to computational thinking for real-world problems](https://github.com/mitmath/18S191)

## [1. Install Julia on Ubuntu](https://danillolima.com/linux/instalando-julia-1-0-0-no-ubuntu-18-04/)

## 2. Install new package on Julia

```
$ julia
> using Pkg
> Pkg.add("Pluto")
```

## 3. Create a notebook with Pluto

```
$ julia
> import Pluto
> Pluto.run()
```

> Go to the http://localhost:1234/ on your browser