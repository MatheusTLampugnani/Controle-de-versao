```
# Projeto de Gerência de Configuração de Software
```

-----

```
Este repositório foi criado como parte de uma atividade para demonstrar os principais conceitos e práticas da **Gerência de Configuração de Software (GCS)**, como controle de versão, criação de branches e rastreabilidade de mudanças.
```

-----

#### **Histórico de Versões (Commits)**

Liste os commits que você fez, um por um. Para cada um, descreva a versão do software e as mudanças introduzidas. Inclua as mensagens de commit que você usou.

**Versão 1.0**

  - **Commit:** `Initial commit: first version of the software`
  - **Descrição:** Criação do arquivo `hello.py` com uma mensagem simples. Este commit representa o ponto de partida do projeto.

**Versão 1.1**

  - **Commit:** `Added a second message to the software`
  - **Descrição:** Modificação no arquivo `hello.py` para incluir uma nova linha de texto. Este commit demonstra a atualização e a evolução do software.

**Versão 1.2**

  - **Commit:** `Refactored the code and created the third version`
  - **Descrição:** Reestruturação do código para usar uma variável. Este commit exemplifica uma refatoração e a criação de uma nova versão do software.

-----

#### **Demonstração de Branching**

Descreva o processo que você utilizou para criar e mesclar a nova funcionalidade. Explique por que o branching é importante (trabalhar em isolamento sem afetar o código principal).

**Branch `feature/greetings`**

  - **Propósito:** Esta branch foi criada para desenvolver uma nova funcionalidade de cumprimento, mantendo-o separado da linha principal de desenvolvimento. Isso garante que o trabalho em andamento não afete a estabilidade do código principal.

**Mesclagem (Merge)**

  - Após a conclusão da funcionalidade, a branch `feature/greetings` foi mesclada na branch `main`. Isso integra a nova funcionalidade ao projeto principal, mostrando um fluxo de trabalho comum no desenvolvimento de software.

-----

#### **Como Usar**

Adicione instruções básicas para que alguém possa clonar o seu repositório e executar o código.

```bash
# Clone o repositório
git clone [URL_DO_SEU_REPOSITORIO]

# Navegue até o diretório do projeto
cd [NOME_DO_REPOSITORIO]

# Execute o arquivo (se aplicável)
python hello.py
```

-----

Lembre-se de substituir os textos entre colchetes (`[ ]`) pelas informações corretas do seu projeto. Um `README.md` bem estruturado como este não só documenta o seu trabalho, mas também demonstra sua compreensão dos conceitos de GCS.
