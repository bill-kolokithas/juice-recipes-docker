FROM elasticsearch:2.4.6
COPY ingredients.txt config/
COPY elasticsearch-inflections-token-filter-2.4.6.zip /
RUN plugin install file:///elasticsearch-inflections-token-filter-2.4.6.zip
