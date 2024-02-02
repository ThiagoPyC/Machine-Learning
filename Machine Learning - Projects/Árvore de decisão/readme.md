# Árvore de decisão

O propósito deste projeto é classificar indivíduos com base em sua propensão para adquirir um novo leitor digital (eReader), visando aprimorar a eficácia das campanhas de marketing. Para atingir esse objetivo, será empregado um modelo de árvore de decisão para analisar os hábitos de consumo dos usuários de um site de e-commerce. 

A abordagem utilizada segue o conceito estabelecido pelo sociólogo Everett Rogers na década de 60, que categorizou os consumidores em grupos como inovadores, early adopters, early majority e late majority. Os dois primeiros grupos são mais propensos a adotar novas tecnologias, enquanto os dois últimos podem adotá-las eventualmente, se julgarem conveniente. 

• Resumo dos dados: 

1. ID_usuário: um identificador numérico associado a cada pessoa que possui uma conte no site. 

2. Gênero: M (masculino) ou F (feminino). 

3. Idade: numérico. 

4. Estado_civil: C – casado, S – não casados (solteiros, viúvos, divorciados, etc.). 

5. Atividade_no_site: Esporádico, Intermitente, Frequente. 

6. Pesquisou_eletronicos_12m: Sim/Não indicando se é o usuário andou pesquisando eletrônicos no site nos últimos 12 meses. 

7. Comprou_eletronicos_12m: Sim/Não indicando se é o usuário comprou eletrônicos no site nos últimos 12 meses. 

8. Pesquisou_mídia_digital_18m: Sim/Não indicando se é o usuário andou pesquisando mídia digital (como mp3) no site nos últimos 18 meses. 

9. Comprou_mídia_digital_18m: Sim/Não indicando se é o usuário comprou mídia digital (como mp3) no site nos últimos 18 meses. 

10. Forma_pagamento: Transferência; Website; Cartão e Boleto bancário. 

        Adoção_eReader: Esse atributo será o rótulo classificador (label). 

        Inovator: quem comprou eReaders de geração anteriores até 1 semana após o lançamento. 

        Early Adopter: quem comprou eReaders de geração anteriores entre 1 e 3 semanas após o lançamento. 

        Early Majority: quem comprou eReaders de geração anteriores entre 3 semanas e 2 meses após o lançamento. 

        Late Majority: quem comprou eReaders de geração anteriores após 2 meses do lançamento. 


A análise será realizada em duas planilhas do arquivo, sendo a primeira chamada TREINAMENTO, contendo registros já classificados, e a segunda chamada VALIDAÇÃO, com novos registros sem classes definidas, usada para avaliar o modelo. Na planilha VALIDAÇÃO, não há um gabarito/label, servindo apenas para simular uma previsão do mundo real. Essa planilha será utilizada para validar visualmente e testar a criação de uma coluna de predição para os casos sem classe definida. 

Antes da construção do modelo, uma análise estatística dos dados é recomendada, destacando que aparentemente não há valores omissos ou inconsistentes, embora seja necessário preparar os dados. O campo ID_usuário, sem relação direta com os consumidores, não será utilizado na modelagem. A classe destino será representada pelo campo Adoção_eReader. 

A construção da árvore de decisão será realizada com base nos dados de treinamento. É feita a exploração de diferentes parâmetros da árvore, incluindo a alteração do critério de seleção de atributos, ajustes nos hiperparâmetros para evitar overfitting e simplificação da árvore para uma complexidade considerada aceitável.

 