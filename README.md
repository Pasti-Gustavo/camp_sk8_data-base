# camp_sk8_data-base
Repositório para entrega do Trabalho final de Modelagem e Banco de Dados do 1º periodo de DSM-Fatec-Franca 
Contextualização do Database:

## Cenário

"Você foi contratado para desenvolver o sistema de gerenciamento de dados de um Campeonato de Skate. O sistema deve controlar o cadastro de categorias, competidores e juízes, além de registrar todo o fluxo de pontuações das duas fases do evento: a Fase Eliminatória e a Fase Final.

Os principais requisitos do sistema são os seguintes:

--Cada campeonato oficial da CBSK deve ser registrado no sistema. Cada campeonato possui um ID, nome do evento, local contendo a (pista/skatepark), a cidade, o estado, a data de início, a data de término além das fases ELIMINATÓRIA e FINAL. 

--Skatistas: Os skatistas participantes devem ser cadastrados no sistema. Cada skatista possui um número de inscrição único, nome, data de nascimento, base, seus patrocinadores.

--Juízes: Os juízes que compõem a banca avaliadora também devem ser registrados. Cada juiz possui um número de identificação único, nome e número de registro na CBSK.

--Fase Eliminatória: Nesta fase, cada competidor tem direito a uma "volta" (run) de exatamente 1 minuto. O sistema deve registrar cada volta realizada, incluindo um código único da volta, o skatista que competiu, as notas de cada volta,  o juiz responsável pela avaliação, a nota final atribuída.

--Fase Final (Jam Session Alternada): A final é disputada apenas pelos 10 melhores skatistas da fase anterior. Cada finalista tem direito a 10 chances de manobra de forma alternada. O sistema deve registrar cada tentativa de manobra individualmente, contendo um código único da tentativa, o skatista finalista, o número da tentativa (de 1 a 10), o juiz que a avaliou e a nota recebida por aquela manobra específica."

## Modelagem Conceitual

--Abaixo link draw.io do diagrama conceitual com base nas entidades e relacionamentos destacados no cenário.
[
https://drive.google.com/file/d/17p-W-90zfP1nBhjiswyL_nAoSiVW8Ekd/view?usp=sharing](https://drive.google.com/file/d/17p-W-90zfP1nBhjiswyL_nAoSiVW8Ekd/view?usp=sharing)

## Modelagem Lógica

--Abaixo link draw.io do diagrama conceitual com base nas entidades e relacionamentos destacados no cenário.

[https://drive.google.com/file/d/17p-W-90zfP1nBhjiswyL_nAoSiVW8Ekd/view?usp=sharing
](https://drive.google.com/file/d/1LRLdWcNYdBDv3L7z649NUZjz8ec0CAZx/view?usp=sharing)

## Modelagem Física

--Scripts de criação das tabelas e relacionamentos do banco de dados.



