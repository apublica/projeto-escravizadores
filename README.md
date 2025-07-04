## Material de apoio - Projeto Escravizadores
Este repositório foi criado para disponibilizar publicamente alguns arquivos e scripts usados no processo de apuração do Projeto Escravizadores. A metodologia adotada pela Agência Pública no Projeto Escravizadores pode ser lida [aqui](). Ela combinou técnicas de genealogia, jornalismo investigativo, análise documental, análise de dados e inteligência artificial para rastrear possíveis vínculos entre autoridades políticas contemporâneas e a escravidão no Brasil. O processo teve início com a definição de uma amostra: 116 autoridades brasileiras — incluindo presidentes, governadores em exercício e senadores da 57ª legislatura (2023–2027). Dentre esses nomes, 33 foram identificados com ancestrais ligados ao sistema escravocrata.

## Fontes documentais: 
* listas nominativas de habitantes (censo populacional do século XIX)
* inventários post-mortem (registros de bens deixados por falecidos, incluindo pessoas escravizadas)
* registros de batismos, nascimentos, casamentos e inventários post-mortem (registros de bens deixados por falecidos, incluindo pessoas escravizadas) de cartórios e paróquias: a maioria disponível no FamilySearch (plataforma de genealogia da Igreja de Jesus Cristo dos Santos dos Últimos Dias, principal ferramenta de busca), mas também foram consultados em cartórios e arquivos públicos de diferentes estados, incluindo o Centro de Preservação, Pesquisa e Referência (CPPR) do Museu da Imigração, a primeira biblioteca afiliada do FamilySearch no Brasil, e Centros de História da Família da Igreja de Jesus Cristo dos Santos dos Últimos Dias.
* DivulgaCand (TSE) - para dados das figuras políticas mais recentes
* Google Acadêmico
* Anúncios de jornais, presentes em periódicos da hemeroteca da Biblioteca Nacional.


## OSINT 
Fizemos buscas documentais específicas com técnicas de OSINT (Open-Source Intelligence), em que foram combinados os nomes dos ancestrais com termos associados à escravidão — como “escravo”, “cativo”, “alforria”, “africano” ou “crioulo” — em acervos históricos, repositórios de pesquisas acadÊmicas e bancos de dados. A equipe analisou cerca de 500 documentos originais. Mais de 200 vínculos entre parentes diretos de políticos e pessoas escravizadas foram registrados.

## ChatGPT, OCR e programação em R

Para lidar com a dificuldade de leitura de manuscritos históricos, frequentemente cursivos e deteriorados, a equipe utilizou inteligência artificial para transcrever automaticamente os documentos digitalizados, seguido de checagem por repórteres da equipe. Criamos um ChatGPT que servia de suporte na transcrição de documentos (ajudando na extração de informações específicas — como nomes, datas, termos jurídicos e relações familiares) e na criação de códigos em R (usando o pacote DiagrammeR) para visualizar as conexões entre as figuras investigadas. 
![Design sem nome (5)](https://github.com/user-attachments/assets/5874c534-feef-4e63-b58b-6f895d0e4343)

![](https://i0.wp.com/apublica.org/wp-content/uploads/2024/11/2-Como-a-Publica-descobriu-os-descendentes-de-escravocratas.png?w=1400&ssl=1)

A representação visual foi feita usando R e Quarto, facilitando a navegação dos jornalistas pelas redes de parentesco em relatórios automatizados. Esse diagrama considera o sistema de numeração genealógica Sosa-Stradonitz (veja um exemplo)

Todas as descobertas foram rigorosamente validadas. A validação exigia a existência de fontes documentais originais, a confirmação de parentesco direto entre o político investigado e a pessoa identificada como escravizadora, além do cruzamento com fontes acadêmicas confiáveis. Após a conclusão da árvore genealógica de cada autoridade, a Pública entrou em contato com todos os nomes citados, enviando previamente os resultados com, no mínimo, 15 dias de antecedência à publicação, oferecendo espaço para resposta ou contestação.




  
![image](https://github.com/user-attachments/assets/8b3ba7fa-0c61-4ee3-ad61-fc59c0b5151e)
