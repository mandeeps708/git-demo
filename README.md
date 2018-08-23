# This is just a demo git repo.

DesignAids

Requirements:
-----------------------------

- Install LaTex
- Install SageMath
- Configure LaTex with Sagemath
- Install biber


Installation of Requirements:
-----------------------------
    1) SageMath

       sudo apt-add-repository -y ppa:aims/sagemath
       sudo apt-get update
       sudo apt-get install sagemath-upstream-binary
    
    2) biber
       
       sudo apt-get install biber
   

To run:
-----------------------------
    1)pdflatex main.tex
    2)biber main
    3)sage main.sagetex.sage
    4)pdflatex main.tex

To create  pdf through script run after changing permissions:
-----------------------------
    ./run
