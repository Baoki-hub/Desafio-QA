# Desafio de Automação de Testes de API - Banco Carrefour

## Descrição

Este projeto contém testes automatizados para a API RESTful que gerencia informações de usuários. Os testes garantem cobertura completa dos endpoints disponíveis e estão integrados a uma pipeline de CI.

## Tecnologias Utilizadas

* Python 3
* Pytest para testes automatizados
* Requests para realizar chamadas à API
* Pytest-HTML para geração de relatórios
* GitHub Actions para CI/CD

## Requisitos

* Python 3 instalado
* Git instalado

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/projeto-teste-api.git
   ```
2. Acesse o diretório do projeto:

   ```bash
   cd projeto-teste-api
   ```
3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Execução dos Testes

Para executar os testes localmente:

```bash
pytest --html=report.html
```

## Pipeline de CI

O pipeline está configurado no GitHub Actions para rodar os testes automaticamente a cada push ou pull request na branch `main`.

* Os testes são executados automaticamente.
* O relatório HTML dos testes é gerado e disponibilizado como artefato na aba de Artefatos da execução da pipeline.

## Relatórios

Os relatórios dos testes são gerados em formato HTML e podem ser acessados diretamente pelo GitHub Actions como artefatos da execução.
