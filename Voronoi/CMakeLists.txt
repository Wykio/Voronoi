# CMakeList.txt : projet CMake pour Voronoi, incluez la source et définissez
# la logique spécifique au projet ici.
#
cmake_minimum_required (VERSION 3.8)

project ("Voronoi")

# Ajoutez une source à l'exécutable de ce projet.
add_executable (Voronoi "source/Voronoi.cpp" "header/Voronoi.h")
add_library (VoronoiLib SHARED "source/Voronoi.cpp" "header/Voronoi.h")
# TODO: Ajoutez des tests et installez des cibles si nécessaire.
