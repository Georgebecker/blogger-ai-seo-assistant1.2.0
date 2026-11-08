# Assistente AI Blogger — versão 1.2.0

![Versão 1.2.0](https://img.shields.io/badge/vers%C3%A3o-1.2.0-0ea5e9)
![Status: MVP](https://img.shields.io/badge/status-MVP-f59e0b)
![Licença: MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-22c55e)

Este repositório oferece o pacote para instalação manual da extensão no Chrome e um guia ilustrado. A extensão auxilia na criação e otimização de posts do Blogger com chaves próprias de IA.

## Classificação

- **Propósito:** distribuir e explicar a instalação da extensão.
- **Maturidade:** MVP 1.2.0, instalado manualmente; não publicado na Chrome Web Store.
- **O que estou praticando:** extensões Chrome, IA e segurança.
- **Quem usaria:** autores de blogs no Blogger que tenham suas próprias chaves de IA.

## Metodologia Loop

O desenvolvimento toma como referência o [projeto_loop](https://github.com/Georgebecker/projeto_loop): hipótese, mudança, teste, medição e decisão. Este repositório é focado na distribuição do pacote e no guia de instalação.

## Baixar e instalar

1. Baixe [`assistente-ai-blogger-v1.2.0.zip`](loja/assistente-ai-blogger-v1.2.0.zip) e extraia os arquivos.
2. No Chrome, abra `chrome://extensions` e ative **Modo do desenvolvedor**.
3. Clique em **Carregar sem compactação** e selecione a pasta extraída que contém `manifest.json`.
4. Configure suas chaves no popup da extensão. Elas ficam **criptografadas**.

Veja o [guia ilustrado completo](docs/GITHUB_INSTALACAO.md). As capturas do guia mostram a versão 1 e podem diferir visualmente da versão 1.2.0.

## Diferença da versão 1

Na versão 1.2.0, as chaves ficam **criptografadas** no navegador e a extensão pode desbloqueá-las automaticamente no editor do Blogger após a configuração. Use **Bloquear** para remover a autorização automática.

## Próximos passos

- Adicionar novos modelos de IA.
- Adicionar novas funcionalidades ao assistente.
- Integrar uma API adicional para geração de imagens.

## Segurança e limitações

- O ZIP distribuído não deve conter suas chaves. Configure-as somente na extensão instalada no seu navegador.
- O uso dos provedores de IA pode gerar cobranças; consulte as condições de cada provedor.
- A instalação é manual, e as capturas disponíveis são da versão 1.
- Revise o conteúdo sugerido pela IA antes de publicar.

## Contribuir

Iniciantes podem sugerir melhorias para o guia ou para o processo de instalação. Colegas podem abrir uma issue com dúvidas, problemas ou propostas. Eu reviso as contribuições e ajudo no que puder.

## Licença e contato

[MIT](LICENSE).
George Herman Becker — [LinkedIn](https://www.linkedin.com/in/georgehbecker/)

## Tags do GitHub

```text
chrome-extension, blogger, seo, typescript, loop-engineering
```
