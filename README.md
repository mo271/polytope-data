# polytope-data

Data sets of polytopes, combinatorial spheres and equiareal triangulations by
Moritz Firsching. The files were previously hosted at
`ftp://ftp.imp.fu-berlin.de/pub/moritz/`; the directory layout is the same.

A description of each data set and of the file formats is on the
corresponding page of [firsching.ch](https://firsching.ch):

| Directory | Contents | Page |
|---|---|---|
| [`classification/`](classification) | all combinatorial 3-spheres and 4-polytopes with up to 9 vertices, with realizations or non-realizability certificates | [firsching.ch/polytopes](https://firsching.ch/polytopes) |
| [`inscribe/`](inscribe) | inscribed realizations of simplicial 3-spheres with up to 10 vertices and of 3-spheres with small valence | [firsching.ch/polytopes](https://firsching.ch/polytopes) |
| [`inscribe/neighborly/`](inscribe/neighborly) | inscribed realizations of neighborly polytopes | [firsching.ch/polytopes](https://firsching.ch/polytopes) |
| [`equiarea/`](equiarea) | equiareal embeddings of 4-connected triangulations of the triangle | [firsching.ch/equiarea](https://firsching.ch/equiarea) |

## Large files

Files larger than 50 MB are not in the repository. They are attached,
xz-compressed, to the [latest release](https://github.com/mo271/polytope-data/releases/latest):

- `classification/all3spheres9vertices.txt`
- `inscribe/polytopalsimplicialspheres10_4.txt`
- `inscribe/neighborly/neighborly10_5inscribed.txt`
- `inscribe/neighborly/neighborly11_6inscribed.txt`
- `inscribe/neighborly/neighborly12_4inscribed.txt`
- `equiarea/tris15.txt`

## License

[Apache License 2.0](LICENSE)
