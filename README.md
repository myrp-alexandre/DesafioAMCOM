# Teste de desenvolvimento .NET (C#) - AMcom

Implemente uma Web API que permita consultar e listas as 5 Unidades Básicas de Saúde (UBSs) mais próximas das coordenadas de latitude e longitude fornecidas como parâmetro e apresente o resultado ordenado pela avaliação de desempenho dessas unidades, da mais alta para a mais baixa.

Você deve carregar um arquivo, disponível no projeto src\AMcom.Teste.DAL, contendo as UBSs e codificar os métodos nas camadas da aplicação, conforme as instruções de cada camada que constam nos arquivos README.md.

**IMPORTANTE: O caminho do arquivo descompactado deve ser informado dentro do Appsettings dentro da camada de WebApi e camada de Service.Tests**

### Instruções

Para realizar o teste, faça um clone do repositório e após concluída a implementação, subir em um repositório no github ou enviar por e-mail para **selecao@amcom.com.br**. **IMPORTANTE: Se for enviar o projeto por e-mail, remover as pastas `bin` e `obj` de cada projeto e compactar o diretório da solução.**

### Solução

A solução está divida nas seguintes camadas:

* Web API - Camada de Web API que deverá expor um método HTTP GET para retornar os dados solicitados no exercício.
* Services - Camada de lógica de aplicação, que deve ser consumida pela Web API com as regras de negócio do exercício.
* DAL - Camada de acesso a dados, onde a carga e disponibilização dos dados da aplicação devem ser implementadas.
* IoC - Camada de registor de injeção de dependencias, onde é relacionado as interfaces com as classes e registrados no container.

A estrutuda da aplicações está conforme abaixo:

src\AMcom.Teste.WebApi

src\AMcom.Teste.Service

src\AMcom.Teste.DAL

src\AAMcom.Teste.IoC

test\AMcom.Teste.Service.Tests

**Cada projeto das camadas listadas acima contém um arquivo README.md com mais detalhes sobre como a implementação deste exercício deve ser feita.**
