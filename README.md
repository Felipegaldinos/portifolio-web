# ProCode Solutions

Site de apresentação de serviços, projetos e contato.

## Recursos

Páginas HTML e formulário de contato com chamada ao EmailJS.

## Tecnologias

HTML, CSS e JavaScript; sem etapa de build npm na estrutura analisada.

## Executar localmente

Sirva os arquivos por HTTP; uma opção com Python 3 instalado:

```sh
git clone https://github.com/Felipegaldinos/portifolio-web.git
cd portifolio-web
python -m http.server 8000
```

Abra http://localhost:8000. Recursos de terceiros, quando usados, exigem conexão com a internet.

## Onde começar no código

- `index.html` — ponto de entrada para entender o projeto.

## Estado atual

O envio depende da configuração do EmailJS em contato.html: serviço, template e chave pública do cliente. Chaves públicas de SDK não substituem as restrições do serviço; não inclua credenciais privadas no navegador.

## Autoria

[Felipe Galdino](https://github.com/Felipegaldinos). Consulte os arquivos do repositório para os termos de licença aplicáveis.
