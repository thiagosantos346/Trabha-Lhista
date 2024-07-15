# Trabha-Lhista

## Plataforma Conversacional Confiável Informacional e de apoio a Denúncias de Assédio e Discriminação no ambiente organizacional 

A prova de conceito do bot, pode ser acessada aqui: [@Traba_Lhistabot](https://t.me/Traba_Lhistabot).
Conta com a seguites features implementadas:
1. Filtro de contexto.
2. Saudações de boas vindas.
3. Menssagens padrões de encerramento.
4. Detecção de caso para denuncias.
5. Simulação de integração a denuncias.
6. Respostas focadas em assédio e descriminação no trabalho.

## Arquitetura proposta para o bot pode ser vista abaixo:
![arc](imgs/thraba-lhista-bot-b.png)

### Prompt's padrão utilizado na POC:
1. ``` Olá sou a <b>Traba Lhista</b>, e quero te ajudar com o que você está passando, me conte se sofreu algum tipo de assédio ou descriniação, caso não tenha certeza me conte mesmo assim, que vou te ajudar. Você é a uma atendende de uma central de denuncias de casos de assédio e descriminação no ambientes de trabalho. Deve responde de forma cuidadosa, humanizada e presar pela orientação. Seu idioma é o português brasileiro, mas não precisa ser tão formal na escrita. A formataçãao do texto é HTML. Inclua emojis. Caso necessário pergunta a cidade pessoa e forneça números ou portais para que ela possa fazer denuncias, ou indicar locais para que ela possa ter ajuda. ```


## Base de dados que devem ser utililizadas no RAG: 
1. [Biblioteca Digital da Câmara dos Deputados](https://bd.camara.leg.br/bd/)
2. [Biblioteca do Conselho da Justiça Federal](https://www.cjf.jus.br/cjf/biblioteca)
3. [Supremo Tribunal Federal](https://portal.stf.jus.br/)
4. [Repositório da UFRGS](https://lume.ufrgs.br/)
5. [Superior Tribunal de Justiça](https://bdjur.stj.jus.br/jspui/)
6. [Escola Superior do Ministério Público da União](https://escola.mpu.mp.br/)
7. [Biblioteca Digital do Senado Federal](https://www2.senado.leg.br/bdsf/)
8. [Diário Oficial da União](https://www.in.gov.br/inicio)
9. [Diário da Justiça Eletrônico](https://www.stj.jus.br/sites/portalp/Processos/Diario-da-Justica-Eletronico)
10. [Banco de Teses USP](https://teses.usp.br/index.php?option=com_jumi&fileid=30&Itemid=162&lang=pt-br&id=2)
11. [Banco de Teses e dissertações da UnB](http://repositorio.unb.br/jspui/)
12. [Biblioteca Digital da Unicamp](https://www.bibliotecadigital.unicamp.br/bd/)
13. [LexML Brasil](https://www.lexml.gov.br/)
14. [Portal de Periódicos da CAPES](https://www-periodicos-capes-gov-br.ezl.periodicos.capes.gov.br/index.php?)
15. [Jurisprudência TST ](https://jurisprudencia.tst.jus.br/)

---    
## Fontes :
1. [RAG using bert-base and mistral-base](https://www.kaggle.com/code/ttminh27/rag-using-bert-base-and-mistral-base)
2. [Self host LLM with EC2, vLLM, Langchain, FastAPI, LLM cache and huggingFace model](https://medium.com/@chinmayd49/self-host-llm-with-ec2-vllm-langchain-fastapi-llm-cache-and-huggingface-model-7a2efa2dcdab)
3. [NLP • Retrieval Augmented Generation](https://aman.ai/primers/ai/RAG/)
4. [RAG: Retrieval-Augmented Generation In Advancing LLMs](https://medium.com/@kagglepro.llc/rag-retrieval-augmented-generation-in-advancing-llms-5f2331ee7c81)
5. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
6. [15 Bases de dados de Direito com acesso gratuito](https://regrasparatcc.com.br/bases-de-dados/15-bases-de-dados-de-direito-com-acesso-gratuito/)
