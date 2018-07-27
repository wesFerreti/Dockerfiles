FROM microsoft/mssql-server-linux:2017-latest

LABEL key="WesleyFerreti" 

EXPOSE 1433
ENV ACCEPT_EULA="Y"
ENV SA_PASSWORD="Senha123"
ENV MSSQL_PID="Express"
RUN cd /home && mkdir BancoDeDados
ENV MSSQL_DATA_DIR="/home/BancoDeDados"
ENV MSSQL_LOG_DIR="/home/BancoDeDados"
#Databases
VOLUME [ "/data" ]

CMD [ "/opt/mssql/bin/sqlservr" ]





