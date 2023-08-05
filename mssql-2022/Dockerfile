FROM mcr.microsoft.com/mssql/server:2022-latest

# Required
ENV ACCEPT_EULA=Y
ENV MSSQL_SA_PASSWORD=P4ssw%rd

EXPOSE 1433/tcp

# Adding tools to path
ENV PATH="$PATH:/opt/mssql-tools/bin"

RUN echo mssql-tools added to your path!
RUN echo $PATH
RUN echo The password setted was $MSSQL_SA_PASSWORD, please consider change it.
