# Objetivo
Hello World com Spring Batch.

## Iniciando

- `git clone https://github.com/sergio-aliceral/hello-spring-batch.git`
- `cd hello-spring-batch`

## Pré-requisitos
- `mvn --version`<br>

Você deverá ver a indicação da versão do Maven instalada e a versão do JDK. Observe que o JDK é obrigatório, assim como a definição das variáveis de ambiente **JAVA_HOME** e **M2_HOME**.

## Limpar, compilar e empacotar
- `mvn clean install`<br>

Gera arquivo _hello-spring-batch.jar_ no diretório _target_.

## Executando a aplicação
- `java -jar target/hello-spring-batch-1.0.jar`<br>

Executa o aplicativo por meio do arquivo jar criado pelo comando `mvn clean install`, conforme comentado anteriormente.
