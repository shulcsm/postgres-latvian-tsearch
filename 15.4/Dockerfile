FROM postgres:15.4

RUN localedef -i lv_LV -c -f UTF-8 -A /usr/share/locale/locale.alias lv_LV.UTF-8
ENV LANG lv_LV.UTF-8

COPY ./tsearch_data/ /usr/share/postgresql/15/tsearch_data/
