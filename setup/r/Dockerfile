# docker inheritance
FROM bioconductor/bioconductor_docker:3.21

# install R packages
RUN R -e "install.packages('pak', repos = 'https://r-lib.github.io/p/pak/stable/')"
RUN R -e "options(BiocManager.version = '3.21'); pak::pak(c('ggpubr', 'clustree', 'anndataR', 'Seurat'))"
