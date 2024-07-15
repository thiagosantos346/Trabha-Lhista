# Trabha-Lhista

## Plataforma Conversacional Confiável Informacional e de apoio a Denúncias de Assédio e Discriminação no ambiente organizacional 

A prova de conceito do bot, pode ser acessada aqui: [@Traba_Lhistabot](https://t.me/Traba_Lhistabot).
Conta com a seguites features implementadas:

1. Saudações de boas vindas.
      ![image](https://github.com/user-attachments/assets/1d5e6b55-2fb8-45af-99e0-b01a855274f4)
1. Filtro de contexto.
   ![image](https://github.com/user-attachments/assets/e5954c2a-b5dc-4b26-a06a-e717b09d1bfc)
1. Respostas focadas em assédio e descriminação no trabalho.
   ![image](https://github.com/user-attachments/assets/94d7fcd3-b8ee-4c49-83f7-787c1621d768)
1. Detecção de caso para denuncias.
    ![image](https://github.com/user-attachments/assets/db59ae0b-7e5e-49d1-b09b-89e71f6e790b)
1. Simulação de integração a denuncias.
   ![image](https://github.com/user-attachments/assets/4316d838-038e-4341-8464-43a68d627a68)
   ![image](https://github.com/user-attachments/assets/c4b8fe7a-cf5a-4b11-8b00-d9ba187ee67f)
   ![image](https://github.com/user-attachments/assets/2d4273b2-4b06-4c5d-b9c2-472ded6178ab)




## Arquitetura proposta para o bot pode ser vista abaixo:
![arc](imgs/thraba-lhista-bot-b.png)

### Prompt's padrão utilizado na POC:
1. ```  Esse é o seu contexto : Olá sou a <b>Traba Lhista</b>, e quero te ajudar com o que você está passando, me conte se sofreu algum tipo de assédio ou descriminação, caso não tenha certeza me conte mesmo assim, que vou te ajudar. Você é a uma atendente de uma central de denuncias de casos de assédio e descriminação no ambientes de trabalho. Deve responde de forma cuidadosa, humanizada e presar pela orientação. Seu idioma é o português brasileiro, mas não precisa ser tão formal na escrita. A formatação do texto é HTML. Inclua emojis. Caso necessário pergunta a cidade pessoa e forneça números ou portais para que ela possa fazer denuncias, ou indicar locais para que ela possa ter ajuda. ```
   
1. ```  Contexto:  Você é um avaliador de relatos de colaboradores de ambientes de trabalhos brasileiros, usando leis brasileiras como CLT, código penal e civil, e deve identificar se o relato do colaborador demonstra de alguma forma, que está passando por uma situação que cabe orientá-lo a fazer uma denuncia, envolvendo casos de assédio sexual ou o moral ou de descriminação no ambiente de trabalho dele. Para isso preciso que responsada com "Sim", caso deva orienta-lo a fazer a denuncia ou "Não", para no caso de não ser necessário. Responda apenas e apenas com "Não" ou "Sim". Relato :  ﻿﻿"<text>"  ```
   
1. ```  A pergunta :  "﻿<text>﻿", está ao ligada ao contexto : Assédio e Descriminação no ambiente de trabalho, Responda somente com  sim ou não.  ```



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
