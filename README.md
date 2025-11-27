# README_Controle_de_Roedores
Este repositório contém a documentação completa sobre o controle de roedores, explicando como registrar os dados nas planilhas, utilizar os recursos do dashboard do Power BI e interpretar os resultados.
--
## 1️⃣ Caminho de Acesso

As planilhas e dashboards estão armazenados em:
`"X:\Gerencia de Produção\Leitura Roedores Bisavós - BI"`

Cada unidade possui:

- sua própria pasta  
- planilha e dashboard individuais  
- um dashboard geral na pasta principal  

---
# 2️⃣ Estrutura das Tabelas  

O controle é composto por:

- **Tabela "Coordenadas ratoeiras"**  
- **Tabela "Roedores"**

---

## 🟥 Tabela Coordenadas Ratoeiras  

Tabela contendo as posições X e Y de cada ratoeira.

### ✔ Como foi construída  
- Baseada nos mapas das unidades (DSV).  
- Coordenadas podem ser retiradas de forma simples utilizando o Paint.  
- Cada ratoeira tem suas coordenadas X/Y conforme o mapa.

### ✔ Para que serve  
- Geração do **mapa interativo** no Power BI.  
- Representação visual do nível de consumo por ratoeira.  

### ✔ Alterações
Caso seja necessário inserir novas ratoeirasou mover alguma:
- Inserir novas ratoeiras seguindo o padrão.  
- Atualizar coordenadas em caso de mudança de posição.

<img width="563" height="410" alt="image" src="https://github.com/user-attachments/assets/ccddb5dd-3db3-4475-85c4-1e8e77266326" />

---
🟥 Tabela Roedores

Esta tabela registra quinzenalmente as ratoeiras de acordo com o local, área, leiturista e registros de consumo (segundo a tabela de Leitura que possui as leituras e avaliações dos leituristas). Dessa forma, a tabela traz o consumo numérico, status e nível de consumo de cada ratoeira. 

Consumo numérico #O consumo numérico é uma conta feita com base nas somas obtidas a patir do consumo de uma determinada ratoeira conta: __Soma Neg*0 + SOMA Toc.*0,1 + SOMA 1/4*0,25 + SOMA 1/2*0,5 + SOMA 3/4*0,75 + SOMA 1*1 
Status: Negativo, Toque ou Consumo.                 #O status é utilizado para o cálculo do Consumo
Consumo: Negativo, Toque, Baixo, Médio e Alto.      #O consumo indica no mapa o nível de consumo que a ratoeira apresenta (Legenda:)

### Passo a Passo para Preenchimento

1. Abrir a tabela de Leitura fornecida pelo admnistrativo; #É possível também fazer o preenchumento manual direto na tabela "Roedores" sem passar pelos passos 1 e 4.

## Exemplo Tabela de Leitura
<img width="846" height="343" alt="image" src="https://github.com/user-attachments/assets/ab2b7b93-4bab-48f2-9d92-1b4e540fe77f" />

--

2. Abrir a aba que estiver sendo registrada na Tabela "Roedores"
3. Preencher as colunas **Data, Local, Área, Número da Ratoeira e Leiturista** de acordo com a tabela de Leitura para um registro quinzenal; #Copie essas colunas da última leitura e cole em baixo

<img width="866" height="287" alt="image" src="https://github.com/user-attachments/assets/59371374-72a0-4e85-a11e-b4db16ca3268" />

4. Copiar os dados dos valores do consumo das linhas de **Negativo até Troca** das ratoeiras da tabela de Leitura;

<img width="460" height="128" alt="image" src="https://github.com/user-attachments/assets/497b5733-0898-45f8-a43d-41af8e38bbf6" />

5. Colar (TRANSPONDO) na tabela "Roedores" os dados; #(Ctrl v + Ctrl + T)

<img width="864" height="289" alt="image" src="https://github.com/user-attachments/assets/b01aeed7-cbe5-44dd-ada0-2b63dd175ec0" />

6. Preencher motivos da troca + observações;

<img width="866" height="286" alt="image" src="https://github.com/user-attachments/assets/53ed7ca8-ba06-4f9e-b175-56dcffa1cb55" />

7. Salvar Planilha.

---
## 3️⃣ Visualização Power BI

#Para abrir os arquivos .pbix de Power BI é necessário ter o software instalado. Caso tenha dúvidas na instalação do programa solicitar ao TI para baixar e instalar, porém é só procurá-lo na loja da Microsoft Store. Como o aplicativo de BI da empresa oficial é o QLIK podemos utilizar apenas a versão gratuita do Power BI sem as opções de compartilhamento que estão na versão paga, portanto para visualizar os dados é necessário que a pessoa que for apresentá-los tenha o aplicativo baixado em sua máquina.

🟥 Controle Roedores Geral

Esse dashboard permite ter uma visualização geral de um conjunto de unidades. Assim, ele da o consumo numérico total das unidades permitindo a comparação delas para as partes interessadas. Nesse dashboard é possível visualizar o consumo mensal das unidades selecionando um intervalo de tempo (data), além de visualizar o consumo de iscas por Unidade e suas respectivas áreas, com um filtro ainda para as áreas dos núcleos. Por fim, os gráficos na parte inferior indicam se houve consumo no período de tempo selecionado nas áreas de mais importância (os núcleos) podendo focar caso haja consumo de iscas dentro dos núcleos e agir rapidamente.

<img width="948" height="539" alt="image" src="https://github.com/user-attachments/assets/d0cf2a43-2704-448f-8c40-c896e476481e" />

Sempre que abrir é necessário garantir que o dashboard esteja com as atualizações mais recentes que foram feitas na planilha, assim é necessário clicar em atualizar.

<img width="1365" height="720" alt="image" src="https://github.com/user-attachments/assets/7458398a-e9e7-4ec7-be3c-142a33f7bb5d" />

Para visualizar o dashboard em modo de tela cheia é necessário publicá-lo no seu workspace do Power BI e clicar no link que será gerado para o Power BI online

<img width="1360" height="717" alt="image" src="https://github.com/user-attachments/assets/f7fa20fa-6d09-4859-9fbb-eb0a40c86d83" />


Modo apresentação Power BI online
<img width="1359" height="671" alt="image" src="https://github.com/user-attachments/assets/605ce595-e2e2-4ab2-b86c-54abc1d23c6c" />


🟥 Controle Roedores de cada Unidade

Esse dashboard permite ter uma visualização das leituras de ratoeiras para agir de forma mais rápida e precisa em caso de algum eventual risco ao aviário. Ele mostra o consumo geral da uidade além de ter uma guia para cada área da unidade e por fim uma guia para controle de estoque do número de iscas de roedores que estão sendo usadas e trocadas.

A guia evolução mensal mostra o consumo mensal da unidade e suas respectivas áreas, podendo filtrar por data e área da unidade. Além disso, ela mostra o consumo numérico de cada área e permite ter uma visualização e ação ágil caso tenha tido consumo em algum núcleo.

<img width="946" height="538" alt="image" src="https://github.com/user-attachments/assets/fe04774a-4cb0-4b94-ae19-9ef621142108" />

A guia de cada parte da unidade permite visualizar um mapa interativo das ratoeiras mostrando como está o consumo de cada ratoeira no dia específico selecionado #(Legenda de consumo). Além disso, permite filtrar por data, área e tipo de consumo. Ele mostra também uma tabela com o nome de todas as ratoeiras mostrando os motivos das trocas e observações que foram anotadas na leitura das ratoeiras na tabela Roedores. Ele mostra também um gráfico para evolução de consumo das ratoeiras, sendo possível selecionar no mapa ou na tabela uma ratoeira para ver a evolução de consumo dela com o passar do tempo, permitindo avaliar se o possivel roedor foi morto ou continua ali. Por fim, há um gráfico que mostra a evolção de consumo por área para avaliar a evolução de consumo das áreas daquele local da unidade conforme o passar do tempo.

<img width="750" height="581" alt="image" src="https://github.com/user-attachments/assets/57c9fddc-9f97-44a9-b2d6-bbf3ae6487e1" />

A gui controle de troca de iscas permite a visualizçaão da quantidade de trocas em cada parte da unidade, permitindo avaliar se estão tendo muitas trocas (mais ou menos que o normal) uma noção se o colaborador que faz a leitura está trocando corretamente as iscas e quais épocas do ano há mais trocas e por quais motivos.

<img width="920" height="512" alt="image" src="https://github.com/user-attachments/assets/9ab80e07-4d9c-4da9-9074-b13b4ecbfa63" />


## 4️⃣ Limitações e Possíveis Erros

- Alguns dados podem estar preenchidos de forma errada na planilha de leitura fornecida pelo admnistrativo ou com dados faltantes, quando isso cocorrer confira o material original feito pelo leiturista e notifique o caso ele também tenha esquecio de preencher alguma dado.
- Caso sejam adicionadas novas ratoeiras ou a sua posição seja alterada nos mapas, os dados passados daquela ratoeira ou a falta de uma podem gerar inconsistências nos mapas e gráficos do Power BI.
- Qualquer dúvida sobre treinamento de colaboradores quanto a leitura de ratoeiras consultar o **POP 10-05**
- Dados podem ficar incorretos se a planilha não for salva corretamente.
- Confira sempre antes de salvar a planilha se você está conectado ao VPN ou a rede da empresa.
- Alterações nas coordenadas sem atualizar a tabela de ratoeiras podem gerar gráficos errados.  
- Alguns filtros do Power BI podem não atualizar se a fonte de dados não estiver sincronizada.

## 5️⃣ Sugestões

- Quaisquer sugestões de layouts, implementações ou alterações nas tabelas ou dashboards são muito bem vindas. Lembre-se esse material foi criado para facilitar o trabalho de todos!

## 6️⃣ Créditos / Referências

**Matheus Santini** – Trainee de Produção Bisavós
Email: msanini@aviagen.com









