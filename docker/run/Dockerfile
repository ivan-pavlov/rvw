## Emacs, make this -*- mode: sh; -*-

FROM rvowpalwabbit/ci

LABEL org.label-schema.license="GPL-2.0" \
      org.label-schema.vcs-url="https://github.com/rvw-org/rvw" \
      maintainer="Dirk Eddelbuettel <edd@debian.org>"

## If on CRAN, install the latest version from CRAN
#RUN install.r ...

## Alternatively, install from Github (after first installing remotes)
RUN install.r remotes && installGithub.r rvw-org/rvw

CMD ["bash"]
