# Projeto estacionamento

## Descrição
Você faz parte do time que construirá um sistema de controle para um estacionamento.  
Você foi imcumbido de implementar a funcionalidade 'estacionar' que recebe como parametro um carro préviamente cadastrado no sistema e a vaga para qual ele se destina.
Os requisitos são:  
Um carro não pode ser estacIonado em uma vaga que já esteja ocupada.  
Uma vez que todas as vagas estejam ocupadas não deve ser permitida a entrada de novos carros.  
Desafio, implementar método que retira o carro da vaga.

## Pré-requisitos
Para executar este projeto, você precisa ter instalado:
- Java JDK 18 ou superior
- Maven 3.6 ou superior

## Configuração
Configure as variáveis de ambiente necessárias antes de iniciar a aplicação. Por exemplo:
- `JAVA_HOME` apontando para o diretório de instalação do JDK.

## Como Executar Localmente
Siga os passos abaixo para executar a aplicação localmente:

1. Clone o repositório:
   ```bash
   git clone [URL_DO_REPOSITORIO]
   cd [NOME_DO_REPOSITORIO] 
   ```
2. Compilar o projeto:
   ```bash
   mvn clean install
   ```
3. Executar a aplicação:
   ```bash
   java -jar target/[nome-do-artefato].jar
   ```
4. Verificação de saude
    ```bash
   curl http://localhost:8080/health
   ```
