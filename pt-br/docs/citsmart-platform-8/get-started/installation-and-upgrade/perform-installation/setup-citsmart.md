Title: Configuração Inicial

# Configuração inicial

Após o deploy do CITSmart, você deverá seguir os passos para finalizar a instalação.

1. Inserir a chave de instalação adquirida junto à CITSmart, e depois disso clicar em "próximo";

2. Informar o tipo de conexão com o SGBD e apontamentos (URL, diretórios, log etc.);

    |Campo|Descrição|Exemplo|
    |-----|---------|-------|
    |Connection Driver|Tipo de SGBD utilizado na instalação |PostgreSQL |
    |System access URL|URL para acesso ao CITSmart | https://citsmart.exemplo.com|
    |Enable loggin on system|Habilitar logs do sistema |True |
    |Name of log file|Nome do arquivo de log | log_citsmart |
    |Path of the folder that will be the LOG file) |Nome da pasta onde os logs serão salvos |/var/tmp |
    |Types: "CIT_LOG" (log file), "DB_LOG" (save in the database) |Tipo de salvamento de logs, em arquivo (CIT_LOG) ou no banco de dados (DB_LOG) | CIT_LOG|
    |Extension of log file|Extensão do arquivo de log (apenas para o tipo CIT_LOG), que será acrescentado ao que você informou em "Nome do arquivo de log" | log |
    |Upload Directory of the repository path|Caminho do ditetório de Upload | /opt/citsmart/upload |
    |GED Directory |Caminho do diretório para GED (Base de conhecimento)| /opt/citsmart/ged|

3. Clicar no item "Finalizar" para efetivar a instalação;

    !!! info "NOTA"
        Quando você clicar em "Finalizar" o processo de instalação do CITSmart iniciará, a partir desse momento serão criadas todas as tabelas no banco de dados

4. Após a instalação com sucesso você será automaticamente redirecionado para a tela de login do CITSmart.

!!! success "Primeiro Acesso"
    O usuário e senha para realizar o primeiro acesso são:
    Usuário: consultor
    Senha: admgoiania516