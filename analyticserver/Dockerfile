FROM opencpu/rstudio

#RUN R -e "install.packages(c('devtools', 'jsonlite'), dependencies=TRUE,repos='http://cran.rstudio.com/')"

RUN sudo apt-get install pandoc -y
RUN R -e "install.packages(c('devtools','xts','fpp2','scatterD3','dplyr','usdm','psych','shiny','tableHTML'),repos='http://cran.rstudio.com/')"   


RUN R -e "devtools::install_github('mattflor/chorddiag')"
#RUN R -e "install_github('ubitech/Physiognomica')"
RUN R -e "devtools::install_github('ubitech/Physiognomica')"
