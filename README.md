#  Studio Neon Dança — Sistema de Cadastro de Alunos

Sistema web para **cadastro e gerenciamento de alunos de uma academia de dança**, desenvolvido com **HTML, CSS e JavaScript puro**, com foco em visual moderno, simplicidade e funcionamento sem backend.

---

## Descrição do Projeto

O **Studio Neon Dança** é uma aplicação front-end que permite cadastrar, editar, listar, filtrar e excluir alunos, armazenando os dados diretamente no navegador utilizando **localStorage**.

O projeto possui uma identidade visual **neon/futurista**, com efeitos de glassmorphism e plano de fundo com imagem local.

---

##  Funcionalidades

###  Cadastro de Alunos
- Nome completo
- Idade
- Estilo de dança (Jazz, Ballet, Hip-hop, etc.)
- Nível do aluno:
  - Iniciante
  - Intermediário
  - Avançado
- Contato (telefone ou e-mail)
- Foto opcional

---

###  Foto do Aluno
- Upload de imagem local
- Pré-visualização da foto
- Caso não haja foto, o sistema gera iniciais do nome
- Imagens armazenadas em Base64 no `localStorage`

---

###  Listagem de Alunos
- Exibição em cards estilizados
- Informações claras e organizadas
- Avatar com foto ou iniciais
- Interface responsiva

---

###  Busca e Filtros
- Pesquisa por:
  - Nome
  - Estilo
  - Nível
- Filtros por:
  - Estilo de dança
  - Nível do aluno

---

###  Edição
- Botão de edição (✎)
- Carregamento automático dos dados no formulário

---

###  Exclusão
- Exclusão com confirmação
- Atualização imediata da interface

---

###  Exportação de Dados
- Exporta todos os alunos cadastrados para um arquivo:
  - `alunos-neon.json`

---

###  Persistência de Dados
- Dados armazenados no navegador com `localStorage`
- Mantém os dados mesmo após fechar o navegador
- Funciona totalmente offline

---

##  Design e Interface

- Paleta de cores:
  - Roxo
  - Azul neon
  - Amarelo
  - Marsala
- Efeitos visuais:
  - Glassmorphism
  - Blur
  - Gradientes
- Plano de fundo:
  - Imagem local
  - Overlay escuro para melhor legibilidade
- Logo animada em SVG



