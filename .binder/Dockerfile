FROM rocker/binder:3.6.0
LABEL maintainer='Eric Ellison'
USER root
COPY . ${HOME}
RUN chown -R ${NB_USER} ${HOME}
USER ${NB_USER}



RUN wget https://github.com/ellison2811/FeRedoxImaging/raw/master/DESCRIPTION && R -e "options(repos = list(CRAN = 'http://mran.revolutionanalytics.com/snapshot/2019-05-01/')); devtools::install_deps()"

RUN rm DESCRIPTION.1; exit 0
