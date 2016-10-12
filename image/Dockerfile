FROM okieoth/d_psql9.3_gis:0.2
RUN localedef -i de_DE -c -f UTF-8 -A /usr/share/locale/locale.alias de_DE.UTF-8
ENV LANG de_DE.utf8

COPY importWith_de.sh /importWith_de.sh

ENTRYPOINT ["/importWith_de.sh"]
CMD ["postgres"]



