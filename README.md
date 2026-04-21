# Taskcheck

O **Taskcheck** é um aplicativo Android desenvolvido em **Kotlin** para gerenciamento de tarefas. O foco do projeto é aplicar conceitos de desenvolvimento mobile, como ciclo de vida de atividades, persistência de dados e interface responsiva, utilizando as melhores práticas do ecossistema Android.

-----

## Tecnologias

  * **Kotlin**: Linguagem oficial para desenvolvimento Android moderno.
  * **Android Studio**: IDE utilizada para construção e debug.
  * **Gradle**: Sistema de automação de build e gerenciamento de dependências.
  * **XML / Jetpack Compose**: (Ajuste conforme o uso) Para construção da interface do usuário.

-----

## Funcionalidades

  * **Cadastro de Atividades**: Interface intuitiva para inserção de novas tarefas.
  * **Visualização em Lista**: Organização clara das tarefas pendentes.
  * **Interatividade**: Marcar tarefas como concluídas ou removê-las.
  * **Performance**: Código otimizado para execução eficiente em dispositivos móveis.

-----

## Como Executar

1.  **Clone este repositório:**
    ```bash
    git clone https://github.com/Louvpiie/Taskcheck.git
    ```
2.  **Abra o Android Studio.**
3.  Vá em `File > Open` e selecione a pasta do projeto.
4.  Aguarde o Gradle sincronizar as dependências (necessário conexão com internet).
5.  Conecte um dispositivo físico ou utilize um emulador e clique no botão **Run** (ícone de "Play" verde).

-----

## Equipe de Desenvolvimento

Projeto colaborativo desenvolvido por:

  * **GABRYELLA SANTOS PINHO**
  * **LOUIE NERY SILVA**
  * **MARIA EDUARDA RITA MARQUES NOLETO**
  * **NATHANAEL VICTOR PAIVA MAGNO**
  * **RAMON MIGUEL ROSA PEREIRA ATAIDES**

-----

## Estrutura do Projeto

Aqui está a organização principal dos diretórios:

```bash
Taskcheck/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/exemplo/taskcheck/  # Código-fonte Kotlin
│   │   │   ├── res/                         # Recursos (Layouts, Strings, Ícones)
│   │   │   └── AndroidManifest.xml          # Configurações do App
│   ├── build.gradle                         # Dependências do módulo app
│   └── proguard-rules.pro                   # Regras de ofuscação
├── gradle/                                  # Wrapper do Gradle
├── build.gradle                             # Configuração global do projeto
└── settings.gradle                          # Definição dos módulos
```
