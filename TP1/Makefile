sources = gui_simple.cpp 
objets = $(sources:.cpp=.o)

#pour retourner la bibliothèque à l'éxécution


CourbeCarre : carre.o
	g++  $^ -o $@ -L /net/cremi/gdebra910e/Bureau/C/TP1/TP1/qcustomplot/sharedlib/compilation -lqcustomplot -lQtGui -lQtCore

carre.o : carre.cpp
	g++ -c $^ -I/usr/include/qt4/QtGui/ -I/usr/include/qt4/ -I//usr/include/qt4/QtCore/  -I/net/cremi/gdebra910e/Bureau/C/TP1/TP1/qcustomplot


GUISimple :$(objets) 
	g++ $^ -o $@ -lQtGui -lQtCore #chercher les librairies

gui_simple.o : gui_simple.cpp
	g++ -c $^ -I/usr/include/qt4/QtGui/ -I/usr/include/qt4/


