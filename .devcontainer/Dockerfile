FROM continuumio/anaconda3:2022.05

RUN apt-get update \
    # && apt-get install zip \
    && conda install -c conda-forge folium \
    && conda install -c conda-forge lightgbm \
    && pip install japanize-matplotlib

CMD [ "/bin/bash" ]