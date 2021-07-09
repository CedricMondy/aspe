<!-- badges: start -->
[![R-CMD-check](https://github.com/PascalIrz/aspe/workflows/R-CMD-check/badge.svg)](https://github.com/PascalIrz/aspe/actions)
<!-- badges: end -->


aspe
====

{aspe} fournit des outils autorisant simplement la plupart des
traitements de base à partir d’une sauvegarde (dump SQL) de la base de
données ASPE de l’OFB. Ces traitements comprennent les calculs
d’abondances, densités, distribution en tailles et la détection de
tendances à l’échelle de la station. Ces calculs sont accompagnés de
fonctionnalités graphiques.

The goal of {aspe} is to is to provide a suite of tools for most of the
common processing of the ASPE database including importation from a SQL
format dump, calculation of abundances, densities, size distributions,
temporal trends for populations at the station level, along with
graphical output.

La base de données ASPE de l’OFB contient toutes les données
d’inventaire par pêche à l’électricité par le CSP, l’ONEMA, l’AFB, l’OFB
ainsi que par certains partenaires sur les rivières de France.

Installation
------------

If necessary, first install the {devtools} R package, then you can
install the released version of {aspe} from
[Github](https://github.com/PascalIrz/aspe) with:

    devtools::install_github("PascalIrz/aspe")


Associated Github repositories
------------

The package comes with a number of associated repos :
- [aspe_data](https://github.com/PascalIrz/aspe_data) : building of the datasets included in the {aspe} package
- [aspe_test](https://github.com/PascalIrz/aspe_test) : R Markdown files to test the {aspe} package and to build the tutorials
- [aspe_demo](https://github.com/PascalIrz/aspe_demo) : R Markdown files to pre-process the fish data for [a dashboard app](https://github.com/CedricMondy/AspeDashboard)
