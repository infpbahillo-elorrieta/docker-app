# Imagen base del contenedor
FROM httpd:2.4

#Añadir el contenido de TSTSWEB
COPY ../TSTWEB/ext/ /usr/local/apache2/htdocs/ext
COPY ../TSTWEB/*.html /usr/local/apache2/htdocs
COPY ../TSTWEB/*.css /usr/local/apache2/htdocs
COPY ../TSTWEB/*.js /usr/local/apache2/htdocs
COPY ../TSTWEB/*.xsd /usr/local/apache2/htdocs
COPY ../TSTWEB/*.xsl /usr/local/apache2/htdocs
