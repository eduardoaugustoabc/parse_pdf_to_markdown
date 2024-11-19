# PDF to Markdown Parser

## Este repositório contém um projeto para converter arquivos PDF em Markdown, oferecendo uma solução simples e eficiente para extrair conteúdo de documentos PDF e formatá-lo em Markdown.

Funcionalidades

Extração de Texto: Lê o texto dos arquivos PDF e converte-o para um formato Markdown.

Preserva Formatação: Converte títulos, parágrafos e listas mantendo a estrutura do documento original.

Suporte a Múltiplos Idiomas: Compatível com textos em vários idiomas.

Simplicidade: Interface fácil de usar, com opções para executar via linha de comando ou como biblioteca em um projeto maior.

Requisitos

Certifique-se de ter instalado:

Python 3.8 ou superior

As seguintes bibliotecas Python:

PyPDF2

markdownify

Para instalar as dependências, use o seguinte comando:

```python
pip install -r requirements.txt
```

Instalação

Clone este repositório:

```python
git clone https://github.com/seu-usuario/pdf-to-markdown.git
```

Navegue até o diretório do projeto:

```python
cd pdf-to-markdown
```

Instale as dependências:

```python
pip install -r requirements.txt
```

Uso

Como script standalone

Execute o script principal passando o caminho para o arquivo PDF e o destino para o arquivo Markdown:

```python
python parse_pdf_to_markdown.py input.pdf output.md
```

Como biblioteca

Importe o módulo em seu próprio projeto:

```python
from pdf_to_markdown import convert_pdf_to_markdown

# Exemplo de uso
convert_pdf_to_markdown('input.pdf', 'output.md')
```

Estrutura do Repositório

parse_pdf_to_markdown.py: Script principal para conversão.

pdf_to_markdown/: Pasta com os módulos principais.

tests/: Testes automatizados para validação do projeto.

examples/: Exemplos de arquivos PDF e seus equivalentes em Markdown.

Testes

Para rodar os testes e garantir que tudo está funcionando corretamente:

```python
pytest tests/
```

Contribuição

Fique à vontade para contribuir com o projeto:

Faça um fork do repositório.

Crie uma branch para sua funcionalidade ou correção:

```python
git checkout -b minha-feature
```

Faça commit das suas mudanças:

```python
git commit -m "Adiciona nova funcionalidade"
```

Envie para o seu fork:

```python
git push origin minha-feature
```

Abra um Pull Request.

Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato

Se tiver alguma dúvida ou sugestão, entre em contato:

Email: eduardoaugustoabc@gmail.com

GitHub: eduardoaugustoabc
