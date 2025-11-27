# README_Controle_de_Roedores
Este repositório contém a documentação completa sobre o controle de roedores, explicando como registrar os dados nas planilhas, utilizar os recursos do dashboard do Power BI e interpretar os resultados.
--
## 1️⃣ Caminho de Acesso

As planilhas e dashboards estão armazenadas em “Leitura de Roedores Bisavós - BI” dentro da pasta de Gerência de Produção: 
`"X:\Gerencia de Produção\Leitura Roedores Bisavós - BI"`

Cada unidade tem uma pasta onde estão localizadas as suas planilhas e seu próprio dashboard, além disso na pasta “Leitura de Roedores Bisavós - BI” existe um dashboard geral para controle de todas as granjas.

--
## 2️⃣ Estrutura das Tabelas

As planilhas estão organizadas em duas tabelas principais:  

- **Tabela "Coordenadas ratoeiras":** contém as posições das ratoeiras de cada local da unidade.  
- **Tabela "Roedores":** contém os registros quinzenais dos controles de ratoeiras feitos pelos colaboradores e que deverão ser preenchidos pelos técnicos de biosseguridade na tabela.

---
🟥 Tabela Coordenadas ratoeiras

Esta tabela contém as coordenadas das ratoeiras em cada galpão.  

- **Como foi feita:** baseado nos mapas de ratoeiras de cada área feito pelo DSV, cada ratoeira tem posição X e Y. Assim, essas coordenadas (jeito mais fácil de ser coletado é colocar a imagem no paint e anotar as coordenadas X e Y) são preecnhidas na tabela de acordo com o número da ratoeira, sua respectiva área e local.
- **Para que servem:** o dashboard usa essas coordenadas para representar no mapa o consumo e ocorrências de cada ratoeira.  
- **Alterações:** se precisar adicionar ou mover uma ratoeira, insira a nova coordenada seguindo o padrão existente.

<img width="563" height="410" alt="image" src="https://github.com/user-attachments/assets/ccddb5dd-3db3-4475-85c4-1e8e77266326" />

---
🟥 Tabela Roedores

Esta tabela registra quinzenalmente as ratoeiras de acordo com o local, área, leiturista e registros de consumo (segundo a tabela de Leitura que possui as leituras e avaliações dos leituristas). Dessa forma, a tabela traz o consumo numérico, status e nível de consumo de cada ratoeira. 

Consumo numérico -- O consumo numérico é uma conta feita com base nas somas obtidas a patir do consumo de uma determinada ratoeira conta: __Soma Neg*0 + SOMA Toc.*0,1 + SOMA 1/4*0,25 + SOMA 1/2*0,5 + SOMA 3/4*0,75 + SOMA 1*1   __
Status: Negativo, Toque ou Consumo.                 -- O status é utilizado para o cálculo do Consumo
Consumo: Negativo, Toque, Baixo, Médio e Alto.      -- O consumo indica no mapa o nível de consumo que a ratoeira apresenta (Legenda:)

### Passo a Passo para Preenchimento

1. Abrir a tabela de Leitura fornecida pelo admnistrativo; --É possível também fazer o preenchumento manual direto na tabela "Roedores" sem passar pelos passos 1 e 4.

## Exemplo Tabela de Leitura
<img width="846" height="343" alt="image" src="https://github.com/user-attachments/assets/ab2b7b93-4bab-48f2-9d92-1b4e540fe77f" />

2. Abrir a aba que estiver sendo registrada na Tabela "Roedores"
3. Preencher as colunas **Data, Local, Área, Número da Ratoeira e Leiturista** de acordo com a tabela de Leitura para um registro quinzenal; --Copie essas colunas da última leitura e cole em baixo

<img width="866" height="287" alt="image" src="https://github.com/user-attachments/assets/59371374-72a0-4e85-a11e-b4db16ca3268" />

4. Copiar os dados dos valores do consumo das linhas de **Negativo até Troca** das ratoeiras da tabela de Leitura;

<img width="460" height="128" alt="image" src="https://github.com/user-attachments/assets/497b5733-0898-45f8-a43d-41af8e38bbf6" />

5. Colar (TRANSPONDO) na tabela "Roedores" os dados; --(Ctrl v + Ctrl + T)
<img width="864" height="289" alt="image" src="https://github.com/user-attachments/assets/b01aeed7-cbe5-44dd-ada0-2b63dd175ec0" />

6.Preencher motivos da troca + observações;
<img width="866" height="286" alt="image" src="https://github.com/user-attachments/assets/53ed7ca8-ba06-4f9e-b175-56dcffa1cb55" />










