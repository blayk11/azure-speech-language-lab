# Azure Speech & Language Studio Lab

Este projeto foi desenvolvido como parte do desafio da DIO para aplicar ferramentas de IA da Microsoft voltadas para análise de fala e linguagem natural.

## Objetivo

Demonstrar o uso prático do Azure Speech Studio e Language Studio para transcrição de áudio e extração de insights linguísticos.

## Ferramentas Utilizadas

- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.azure.com/)
- [GitHub para documentação](https://github.com/)

## Estrutura do Projeto

- `/images`: capturas de tela das etapas
- `/data`: arquivos gerados durante o processo
- `README.md`: documentação completa do desafio

## Etapas Realizadas

1. **Seleção do áudio**  
   Extraído do vídeo [Bitcoin Explained in 45 Seconds](https://www.youtube.com/shorts/kvhjQfqZ4KQ) publicado no youtube, utilizando o site [y2meta](https://y2meta.is/pt34/youtube-to-mp3/).

2. **Transcrição com Speech Studio**  
   Resultado: *Bitcoin represents something totally new that has never existed and that is decentralized money that runs on the Internet that you don't need to trust any third party to hold or use. You basically can choose to hold it by holding a private key. You can either memorize it in your head, have it on a piece of paper, put it on a hardware wallet, or you can trust the third party like Abra or crypto exchange or bank to hold to hold your Bitcoin. That's Bitcoin and. Nothing else. You can move it between two people, You can hold it. That's all it does. It's really meant to act as like a digital gold and eventually act as the base layer for a new monetary system.*

3. **Análise com Language Studio**  
   - Resumo: 
        - Bitcoin represents something totally new that has never existed and that is decentralized money that runs on the Internet that you don't need to trust any third party to hold or use.
        - You basically can choose to hold it by holding a private key.
        - You can either memorize it in your head, have it on a piece of paper, put it on a hardware wallet, or you can trust the third party like Abra or crypto exchange or bank to hold your Bitcoin.
        - That's Bitcoin and nothing else.
        - It's really meant to act as like a digital gold and eventually act as the base layer for a new monetary system.
   - Sentimento: Neutral: 90% (Confidence: 8%)  
        - Apesar do conteúdo ter sido avaliado neutro em 90% do conteúdo, a ferramenta atribuiu apenas 8% de confiança a esse resultado, a causa muito provavelmente se dá a ambiguidade das colocações do texto analisado.

## Aprendizados

- Compreensão do fluxo básico de análise de fala e texto com Azure
- Importância da documentação clara para projetos técnicos
- Potencial de uso em aplicações reais (ex: atendimento, análise de feedback)


## Referências

- [Documentação oficial do Speech Studio](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/)
- [Documentação oficial do Language Studio](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/)