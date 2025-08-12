🏎️ Mario Kart.JS - Desafio DIO
<div align="center"> <img src="./docs/header.gif" alt="Mario Kart" width="400"> </div>
📜 Descrição do Projeto
Implementação de uma simulação de corrida no estilo Mario Kart usando JavaScript puro, desenvolvido como parte do desafio proposto pelo Felipão na Digital Innovation One. O projeto simula corridas entre personagens clássicos do universo Mario com mecânicas baseadas em atributos e rolagem de dados.

🎮 Personagens e Atributos
<table style="border-collapse: collapse; width: 100%; margin: 20px 0;"> <tr> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/mario.gif" alt="Mario" width="60"> <p><strong>Mario</strong></p> <p>Velocidade: 4</p> <p>Manobrabilidade: 3</p> <p>Poder: 3</p> </td> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/peach.gif" alt="Peach" width="60"> <p><strong>Peach</strong></p> <p>Velocidade: 3</p> <p>Manobrabilidade: 4</p> <p>Poder: 2</p> </td> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/yoshi.gif" alt="Yoshi" width="60"> <p><strong>Yoshi</strong></p> <p>Velocidade: 2</p> <p>Manobrabilidade: 4</p> <p>Poder: 3</p> </td> </tr> <tr> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/bowser.gif" alt="Bowser" width="60"> <p><strong>Bowser</strong></p> <p>Velocidade: 5</p> <p>Manobrabilidade: 2</p> <p>Poder: 5</p> </td> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/luigi.gif" alt="Luigi" width="60"> <p><strong>Luigi</strong></p> <p>Velocidade: 3</p> <p>Manobrabilidade: 4</p> <p>Poder: 4</p> </td> <td style="border: 1px solid #ddd; text-align: center; padding: 10px;"> <img src="./docs/dk.gif" alt="Donkey Kong" width="60"> <p><strong>Donkey Kong</strong></p> <p>Velocidade: 2</p> <p>Manobrabilidade: 2</p> <p>Poder: 5</p> </td> </tr> </table>
� Mecânicas do Jogo
🏁 Sistema de Corrida
5 rodadas com segmentos aleatórios

3 tipos de segmentos:

🏎️ Reta: Teste de velocidade (dado + velocidade)

🌀 Curva: Teste de manobrabilidade (dado + manobrabilidade)

⚔️ Confronto: Teste de poder (perdedor perde 1 ponto)

🏆 Condições de Vitória
Sistema de pontuação balanceado

Prevenção de pontuação negativa

Vencedor é quem tiver mais pontos após 5 rodadas

✅ Checklist de Implementação
🧑‍🤝‍🧑 Jogadores
Seleção aleatória de 2 personagens

Atributos individuais para cada personagem

Sistema de objetos para cada jogador

🏁 Pistas e Mecânicas
5 rodadas com segmentos aleatórios

Lógica diferente para cada tipo de segmento

Sistema de rolagem de dados (d6)

Prevenção de pontuação negativa

🏆 Finalização
Comparação de pontuação final

Declaração do vencedor

Tratamento de empates