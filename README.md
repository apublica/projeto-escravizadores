# Material complementar – Projeto Escravizadores

Este repositório reúne arquivos e scripts utilizados no processo de apuração do Projeto Escravizadores, realizado pela Agência Pública. A metodologia completa empregada no projeto pode ser consultada [neste link](https://apublica.org/2024/11/como-a-publica-descobriu-os-antepassados-que-teriam-escravizados/).

## Metodologia

A investigação combinou técnicas de genealogia, jornalismo investigativo, análise documental, análise de dados e inteligência artificial para rastrear possíveis vínculos entre autoridades políticas contemporâneas e o sistema escravocrata brasileiro.

## Amostra

Foram investigados 116 nomes, entre eles:

- Todos os presidentes do Brasil desde a redemocratização;
- Governadores em exercício;
- Senadores da 57ª legislatura (2023–2027).

Dos investigados, 33 foram identificados com ancestrais ligados diretamente à escravidão.

## Fontes consultadas

A apuração se baseou em fontes primárias e secundárias, incluindo:

- Listas nominativas de habitantes e maços de população (equivalentes a censos do século XIX);
- Registros de batismo, nascimento, casamento e inventários post-mortem, muitos disponíveis na plataforma FamilySearch, além de arquivos públicos, cartórios e instituições como:
  - Museu da Imigração (CPPR);
  - Centros de História da Família da Igreja de Jesus Cristo dos Santos dos Últimos Dias;
- Dados eleitorais do DivulgaCand (TSE);
- Google Acadêmico, para busca de estudos sobre as famílias investigadas;
- Hemeroteca da Biblioteca Nacional, com anúncios de jornais históricos;
- Redes sociais.

## Técnicas de OSINT

Foram aplicadas metodologias de inteligência de fontes abertas (OSINT), cruzando nomes de ancestrais com termos como “escravo”, “cativo”, “alforria”, “africano” e “crioulo” em bancos de dados históricos, repositórios acadêmicos e documentos originais. No total, foram analisados cerca de 500 documentos, resultando na identificação de mais de 200 vínculos documentados entre parentes diretos de políticos e pessoas escravizadas.

## Uso de ChatGPT, OCR e programação em R

Para lidar com manuscritos históricos — geralmente cursivos e degradados —, foram utilizadas tecnologias de OCR e inteligência artificial. Um modelo do ChatGPT foi usado para auxiliar na transcrição automática de documentos, extração de informações específicas (nomes, datas, relações familiares, termos jurídicos) e criação de códigos em R com o pacote DiagrammeR.

## Visualização e relatórios

As árvores genealógicas e conexões familiares foram representadas visualmente, inicialmente, por uma [planilha](https://github.com/apublica/projeto-escravizadores/blob/main/Template%20Sosa-Stradonitz.xlsx) baseada no sistema de numeração genealógica [Sosa-Stradonitz](https://docs.ancestris.org/books/user-guide/page/generate-sosa-numbers), e depois por meio do R e do Quarto, para automatizar a criação de relatórios. Os [relatórios](https://github.com/apublica/projeto-escravizadores/blob/main/template_relatorio.qmd) automatizados facilitaram a navegação da equipe jornalística pelas redes de parentesco.

## Validação e direito de resposta

Todas as descobertas foram rigorosamente validadas. Os critérios incluíam:

- Existência de documentos originais;
- Comprovação de parentesco direto entre o político e o escravizador identificado;
- Cruzamento com fontes acadêmicas confiáveis.

Antes da publicação, a Agência Pública entrou em contato com todos os citados, enviando os resultados com pelo menos 15 dias de antecedência, oferecendo espaço para resposta ou contestação.
