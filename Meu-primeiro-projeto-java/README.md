## Introdução

Bem-vindo ao mundo Java no VS Code. Aqui está um guia para ajudá-lo a começar a escrever código Java no Visual Studio Code.

## Estrutura de Pastas

O espaço de trabalho contém duas pastas por padrão, onde:

- `src`: a pasta para manter os arquivos-fonte
- `lib`: a pasta para manter as dependências

Enquanto isso, os arquivos compilados serão gerados na pasta `bin` por padrão.

> Se você quiser personalizar a estrutura das pastas, abra `.vscode/settings.json` e atualize as configurações relacionadas lá.

## Gerenciamento de Dependências

A visualização `JAVA PROJECTS` permite que você gerencie suas dependências. Mais detalhes podem ser encontrados [aqui](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

Claro! Vou ajudar você a criar uma documentação completa para a instalação do ambiente Java no Visual Studio Code (VS Code), desde o download até a configuração final. Aqui está o passo a passo:

---

# Guia de Instalação do Ambiente Java no Visual Studio Code

Este guia descreve o processo de configuração do ambiente de desenvolvimento Java no Visual Studio Code, incluindo o download do JDK, instalação do VS Code, configuração das extensões e a criação de um projeto Java básico.
<br>

## 1. **Download e Instalaçãodo Visual Studio Code**

### Passo 1: Baixar o JDK e VS Code
1. Acesse o site oficial do Visual Studio: [Visual Studio Languages Java Downloads](https://code.visualstudio.com/docs/languages/java).
2. Escolha e baixe o instalador correspondente ao seu sistema operacional (Windows, macOS, Linux).
<br>

### Passo 2: Instalar o Java Coding Pack
1. Execute o instalador do Java Coding Pack baixado.
2. Siga as instruções na tela para concluir a instalação.
3. Caso ainda não tenha o VS Code instalado, ele fará a instalação. Caso já obtenha o VS Code, o sistema de instalação irá identificar.
<br>

## 3. **Configuração do Ambiente Java no VS Code**

### Passo 1: Instalar Extensões Necessárias
1. Abra o VS Code.
2. Vá para a aba **Extensões** (`Ctrl + Shift + X`).
3. Pesquise por **"Java Extension Pack"** e instale este pacote. Ele inclui várias extensões importantes:
   - Language Support for Java™ by Red Hat
   - Debugger for Java
   - Maven for Java
   - Java Test Runner
   - Visual Studio IntelliCode
4. Opcionalmente, instale a extensão **"Material Icon Theme"** para melhorar a visualização dos ícones de arquivos e pastas.
<br>


## 4. **Criando um Projeto Java Básico**

### Passo 1: Criar um repositorio no GitHub
1. No Github vá até repositórios e clique em **New** para criar um novo repositório.
2. Nomeie o novo repositório como: **dio-java-basico**.
3. Selecione a opção **Public** (para deixar seu reositório puclico).
4. Selecione a opção **add a README file** e crie uma mensagem: **Repositorio para armazenar todo conteudo do curso de Java Basico**.
5. Selecione a opção **Gitignore** e escolha a opção **Java**.
6. Clique em **Create a repository**
<br>

### Passo 2: **Integrando o VS Code com o GitHub**
O objetivo é integrar de forma automatizada o repositório local com o repositório remoto.
1. No Vs code, vá até as extensões e procure por: **GitHub Pull Requests** e instale.
2. Instale também a extensão: **GitHub Repositories** e **GitHub Actions**.
3. No VS code vá até o ícone de **perfil**  localizado na coluna do lado esquerdo, acima da engrenagem. 
4. Selecione a opção: **Entrar nas contas de sincronização**
5. Na barra de busca superior irá aparecer: **Entrar com Github**, clique.
6. O sistema irá direcionar para o Github, siga as instruções para finalizar a sincronização.

### Passo 3: **Clonando repositorio remoto no ambiente local**
1. No Vs code aperte **ctrl** + **Shift** + **P**
2. Clique em **git clone**
3. Confirme que deseja clonar. 
4. Ele vai direcionar por segurança para o site **Github** para confirmar. Confirme.
5. No Vs ele irá mostrar os repositórios, clique em **dio-java-basico**. 
6. Automaticamente ele irá abrir o windows, escolha um local de sua preferencia e crie uma pasta nomeada como **Dio**, ou um nome de sua preferência. (todo o conteudo ficará nesta pasta). Selecione a pasta.
7. Automaticamente após a seleção, na parte inferior do VSCode o Git irá perguntar se deseja abrir o repositório clonado, clique em **sim**
8. Pronto, o repositório irá aparecer no ambiente local.

### Passo 4: **Alterando arquivo local e enviando um commit para o repositório remoto**
1. Na pasta **Readme** inclua a mensagem: **Alterando o conteudo de um arquivo de forma local**.
2. Na coluna da lateral esquerda o Git ja irá sinalizar uma alteração, clique.
3. Na mensagem, escreva: **Meu primeiro commmit**.
4. Clique em **Commit** e depois confirme a sincronização.
5. Vá até o ambiente remoto e confirme o commit feito.


### Passo 5: **Criando um projeto Java**
1. Tecle **Ctrl** + **Shift** + **P**
2. Clique em **Create a Java Project**.
3. Selecione a opção: **No build tools**
4. Ele já irá direcionar para o diretorio clonado. Selecione e confirme.
5. Na barra superior, coloque o nome do projeto: **Meu-primeiro-projeto-java**. Ele irá abrir uma nova janela, feche a anterior se isso acontecer.
6. Ele ja irá criar a seguinte estrutura de diretórios:
   ```
   - .vscode/
   - bin/
   - lib/
   - src/
     - App.java
   - README.md
   ```
7. Clique em: **App.java**, ele deve apresentar o seguinte código: 
 ```
public class App {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
 ```
 8. Altere a mensagem **Hello world** para: **Boas Vindas turma DIO**
 9. Na própria tela você irá encontrar a palavra **Run**, clique. 
 10. Novamente na coluna da lateral esquerda o Git ja irá sinalizar uma alteração, clique.
 11. Na mensagem, escreva: **Meu primeiro projeto java**.
 12. Clique em **Commit** e depois confirme a sincronização.
 5. Vá até o ambiente remoto e confirme a inclusão da nova pasta e arquivo relacionado ao projeto.



