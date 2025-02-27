# Image Name: overleaf-texlive-full
# Description: Overleaf CE with full TeX Live installation

FROM sharelatex/sharelatex

# Update tlmgr and install full TeX Live
RUN tlmgr update --self && \
    tlmgr install scheme-full
