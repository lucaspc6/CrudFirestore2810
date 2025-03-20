# Firestore CRUD

Este repositório contém um projeto de aplicativo Android desenvolvido em Kotlin que implementa operações CRUD (Create, Read, Update, Delete) utilizando o Firebase Firestore como banco de dados. O projeto está estruturado para fornecer uma base sólida para desenvolvedores que desejam integrar o Firestore em suas aplicações móveis.

## Estrutura do Projeto

A estrutura de pastas e arquivos do projeto é organizada da seguinte forma:

- **`app/`**: Contém o código-fonte principal do aplicativo, incluindo atividades, fragmentos e recursos.
- **`gradle/`**: Inclui os scripts e arquivos necessários para o sistema de build Gradle.
- **`.idea/`**: Contém configurações específicas do IntelliJ/Android Studio.
- **`.gitignore`**: Especifica arquivos e pastas que devem ser ignorados pelo Git.
- **`build.gradle.kts`**: Script de build principal do Gradle em Kotlin DSL.
- **`gradle.properties`**: Propriedades de configuração do Gradle.
- **`gradlew`** e **`gradlew.bat`**: Scripts para executar o Gradle em ambientes Unix e Windows, respectivamente.
- **`settings.gradle.kts`**: Configurações de build do Gradle em Kotlin DSL.

## Funcionalidades

O aplicativo demonstra as seguintes operações básicas com o Firestore:

- **Criação (Create)**: Adiciona novos documentos à coleção do Firestore.
- **Leitura (Read)**: Recupera e exibe documentos existentes.
- **Atualização (Update)**: Modifica dados de documentos específicos.
- **Exclusão (Delete)**: Remove documentos do banco de dados.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem principal para o desenvolvimento do aplicativo Android.
- **Firebase Firestore**: Banco de dados NoSQL em tempo real para armazenamento e sincronização de dados.
- **Gradle**: Sistema de automação de build utilizado para gerenciar dependências e processos de build.

## Requisitos de Negócio

As regras de negócio implementadas no aplicativo incluem:

- **Validação de Dados**: Antes de adicionar ou atualizar um documento no Firestore, o aplicativo verifica se os dados inseridos pelo usuário atendem aos critérios estabelecidos, garantindo a integridade e consistência das informações.
- **Controle de Acesso**: Implementa permissões para que apenas usuários autorizados possam realizar operações específicas, como exclusão ou atualização de dados sensíveis.
- **Notificações em Tempo Real**: Utiliza recursos do Firestore para notificar os usuários sobre alterações nos dados, garantindo que todos tenham acesso às informações mais recentes.

## Como Executar o Projeto

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/lucaspc6/CrudFirestore2810.git
   ```
2. **Abra o Projeto no Android Studio**: Navegue até a pasta do projeto clonado e abra-o no Android Studio.
3. **Configure o Firebase**:
   - Acesse o [Console do Firebase](https://console.firebase.google.com/).
   - Crie um novo projeto ou utilize um existente.
   - Adicione um aplicativo Android ao projeto do Firebase e siga as instruções para obter o arquivo `google-services.json`.
   - Coloque o arquivo `google-services.json` na pasta `app/` do seu projeto.
4. **Sincronize o Projeto com o Gradle**: No Android Studio, sincronize o projeto para garantir que todas as dependências sejam baixadas e configuradas corretamente.
5. **Execute o Aplicativo**: Conecte um dispositivo Android ou utilize um emulador e execute o aplicativo através do Android Studio.
