# Gerador de Senhas

Este projeto é um gerador de senhas desenvolvido com HTML, CSS e JavaScript. Ele permite criar senhas personalizadas com base nas preferências do usuário, como inclusão de letras maiúsculas, minúsculas, números e caracteres especiais.

## Funcionalidades

- **Gerar Senha:**
  - O usuário pode definir o comprimento desejado da senha.
  - O usuário pode escolher incluir ou não letras maiúsculas, minúsculas, números e caracteres especiais na senha gerada.
  - Feedback informativo é exibido em caso de erros ou quando a senha é gerada com sucesso.

- **Copiar Senha:**
  - O usuário pode copiar a senha gerada para a área de transferência com um clique.
  - Feedback é exibido informando que a senha foi copiada.

## Tecnologias Utilizadas

- **HTML:** Estrutura do formulário e botões de interação.
- **CSS:** Estilização básica da interface (não fornecida aqui, mas necessária para o layout).
- **JavaScript:**
  - Manipulação do DOM para capturar entradas e atualizar saídas.
  - Lógica para geração aleatória de senhas com base nas preferências do usuário.

## Estrutura do Código

### Eventos

1. **Clique em "Gerar":**
   - Captura os valores do formulário (comprimento da senha e opções selecionadas).
   - Valida o comprimento da senha.
   - Chama a função `gerarSenha` para criar a senha.
   - Exibe a senha gerada no elemento correspondente.

2. **Clique em "Copiar":**
   - Copia o texto da senha gerada para a área de transferência.
   - Exibe uma mensagem de feedback ao usuário.

### Funções

- **gerarSenha(comprimento, maiusculas, minusculas, numeros, especiais):**
  - Constrói uma string com os caracteres permitidos com base nas opções do usuário.
  - Gera uma senha aleatória do comprimento especificado.
  - Retorna a senha gerada.

## Como Utilizar

1. Preencha o comprimento da senha desejada no campo de texto.
2. Marque as opções desejadas para personalizar os caracteres da senha (letras maiúsculas, minúsculas, números e caracteres especiais).
3. Clique no botão "Gerar Senha" para criar a senha.
4. Visualize a senha gerada na tela.
5. Clique no botão "Copiar" para copiar a senha para a área de transferência.

## Print do Projeto

Clique [aqui](https://senhanovasegura.netlify.app) para acessar o meu projeto.

![Screenshot_64](https://github.com/user-attachments/assets/eda21955-be26-437a-8ffa-37fb1eca6b92)

---

Espero que este projeto seja útil para suas necessidades de segurança e geração de senhas!

