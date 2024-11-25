# Sistema de Cadastro

Este projeto consiste em um sistema de cadastro para diferentes tipos de usuários, como Pessoas Físicas, Pessoas Jurídicas, Professores, Fornecedores e Alunos. Ele foi desenvolvido para gerenciar registros de forma eficiente e centralizada. O design do sistema foi prototipado no **Figma**, e os diagramas de casos de uso e classes foram criados no **draw.io** e **PlantUML**.

---

## Integrantes do Grupo

| Nome              | GitHub                           | E-mail                  |
|-------------------|----------------------------------|-------------------------|
| Emerson Macedo de Almeida | [@Macedo951](https://github.com/Macedo951) | emersonmacedo951@gmail.com |
| Francisco de Bulhões Mossri | [@fmossri](https://github.com/fmossri) | chicobulhoes@gmail.com |
| Amanda Fraga da Rocha | [@arfraga](https://github.com/arfraga) | fragaamanda@hotmail.com |
| Laura Golombieski Balbinot | [@lauragolombieski](https://github.com/lauragolombieski) | lauragolombieskib@gmail.com |
| Rafael Silva de Oliveira | [@RafaSilva1709](https://github.com/RafaSilva1709) | rafae1silv.rs@gmail.com |



## 2. Diagrama de Casos de Uso

O diagrama de casos de uso identifica as principais interações do **Administrador** com o sistema.

### Figura 1 – Diagrama de Casos de Uso
> Criado com o draw.io: [https://app.diagrams.net/](https://app.diagrams.net/)

![Diagrama de Casos de Uso](images\Diagrama_de_casos_de_uso.png)

---

## 3. Cenários de Casos de Uso

### Ator Principal: **Administrador**
O Administrador é responsável por gerenciar os cadastros do sistema.

### Casos de Uso:
- **Cadastrar Pessoa Física**: Registro de indivíduos.
- **Cadastrar Pessoa Jurídica**: Registro de entidades comerciais.
- **Cadastrar Professores**: Registro específico para professores.
- **Cadastrar Fornecedores**: Registro de fornecedores parceiros.
- **Cadastrar Alunos**: Registro específico para estudantes.

---

## 4. Descrição dos Cenários de Uso

### 4.1 Cadastro de Pessoa Física
- **Ator**: Administrador
- **Descrição**: O ator acessa o sistema e seleciona a opção de cadastro de Pessoa Física.
- **Cenário Principal**:
  1. O sistema exibe um formulário de cadastro.
  2. O ator preenche os campos obrigatórios (nome, endereço, telefone, CPF).
  3. O ator submete o formulário.
  4. O sistema valida os dados e salva o registro no banco de dados.
  5. O sistema exibe uma mensagem de confirmação.
- **Cenários Alternativos**:
  1. O ator não preenche todos os campos obrigatórios:
      - O sistema exibe uma mensagem de erro indicando os campos que precisam ser preenchidos.
  2. O CPF informado já está cadastrado no sistema:
      - O sistema exibe uma mensagem de erro indicando que o CPF já está registrado.
- **Pré-condição**: O ator deve estar autenticado no sistema.
- **Pós-condição**: Os dados da Pessoa Física são salvos no banco de dados.

#### Outras descrições de casos de uso:
- **Cadastro de Pessoa Jurídica**: Mesma estrutura acima, adaptada para campos como CNPJ.
- **Cadastro de Professores, Fornecedores e Alunos**: Mesma estrutura, considerando campos como matrícula ou contrato.

---

## 5. Diagrama de Classes

O diagrama de classes identifica as entidades do sistema e suas propriedades, comportamentos e relacionamentos.

### Figura 2 – Diagrama de Classes
> Criado com o PlantUML: [https://plantuml.com/](https://plantuml.com/)

![Diagrama de Classes](images\Diagrama_de_classes.png)

---

## Protótipo no Figma

O design do sistema foi criado no Figma e pode ser acessado no link abaixo:
[Figma - Sistema de Cadastro](https://www.figma.com/design/TOdmGI75ZVQCVdASLOwHOv/Sistema-de-cadastro?node-id=0-1&t=AfsMvzKcCXFNyyqG-1)

### Telas do Sistema

#### Tela de Login
![Tela de login](images\Tela_login.png)

#### Tela Inicial
![Tela Inicial](images\Tela_Inicial.png)

#### Tela de Cadastro de Pessoa Física
![Cadastro Pessoa Física](images\Tela_cadastro_PF.png)

#### Tela de Cadastro de Pessoa Jurídica
![Cadastro Pessoa Jurídica](images\Tela_Cadastro_PJ.png)

#### Tela de Cadastro de Professores
![Cadastro de Professores](images\Tela_Cadastro_Professores.png)

#### Tela de Cadastro de Fornecedores
![Cadastro de Fornecedores](images\Tela_Cadastro_Fornecedores.png)

#### Tela de Cadastro de Alunos
![Cadastro de Alunos](images\Tela_Cadastro_Alunos.png)

#### Tela de Sucesso no Cadastro
![Sucesso no Cadastro](images\Tela_sucessoCadastro.png)

---

## Como Executar o Sistema

1. Clone o repositório:
   ```bash
   git clone https://github.com/lauragolombieski/PI-Sistema-de-Cadastro.git