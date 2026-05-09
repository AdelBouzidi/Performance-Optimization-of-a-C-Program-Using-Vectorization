# Optimisation des Performances d’un Programme C par Vectorisation

Projet académique réalisé dans le cadre d’un travail pratique portant sur l’analyse de performance, la vectorisation SIMD et l’optimisation de calculs intensifs en C.

Le projet s’appuie sur l’étude et l’optimisation d’algorithmes de multiplication matricielle en utilisant différentes techniques de vectorisation et niveaux de compilation.

---

# Objectifs du projet

Ce travail a pour objectif :

- d’analyser les performances d’un programme C à l’aide des outils Linux `perf stat` et `perf record`
- d’étudier l’impact des niveaux d’optimisation du compilateur (`-O2`, `-O3`)
- d’appliquer des techniques de vectorisation SIMD
- d’évaluer l’influence du *blocking* sur les performances
- de comparer plusieurs configurations afin d’identifier les optimisations les plus efficaces

---

# Technologies et outils utilisés

- Langage C/C++
- CMake
- Linux Perf (`perf stat`, `perf record`, `perf report`)
- SIMD / AVX2 Intrinsics (`<immintrin.h>`)
- Optimisations GCC (`-O2`, `-O3`, `-march=native`, `-ftree-vectorize`)

---

# Compilation du projet

```bash
mkdir build
cd build
cmake ..
make
