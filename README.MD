# Configuração do SonarQube Local

Este projeto tem como objetivo configurar uma instância local do SonarQube utilizando a imagem Community do SonarQube e configurar o banco de dados utilizando o PostgreSQL.

## Pré-requisitos
- Docker instalado
- Docker Compose instalado

## Passos para Configuração

1. **Clone este repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd sonarqube-local
   ```

2. **Inicie o SonarQube**:
   - Navegue até o diretório `docker-sonarqube` e execute:
   ```bash
   docker-compose up -d
   ```

3. **Configuração do Banco de Dados**:
   - Certifique-se de que o PostgreSQL está configurado corretamente no arquivo `compose.yaml`.
   - As credenciais do banco de dados devem ser definidas conforme necessário.

4. **Acesse o SonarQube**:
   - Após a inicialização, você pode acessar o SonarQube em `http://localhost:9000`.
   - As credenciais padrão são:
     - **Usuário**: admin
     - **Senha**: admin

## Contribuições
Sinta-se à vontade para contribuir com melhorias ou correções. Abra uma issue ou um pull request!

## Licença
Este projeto está licenciado sob a MIT License.
