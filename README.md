# Projeto NeoADP

## Sobre

Este projeto tem como objetivo principal a implementação do método PEWS, uma ferramenta de uso dos profissionais da saúde que, com base no estado de uma criança, calcula uma intervenção a partir de um sistema de pontuações. Em outras palavras, esta ferramenta entrega uma solução específica para um(a) menino(a) que apresente determinados sintomas, o que agiliza o processo de diagnóstico e, consequentemente, de tratamento.

Assim, é proposto que o sistema leia os dados dos sensores e atualize a tabela de entrada de dados, gerando relatórios automaticamente. Dependendo da gravidade da situação da criança, o sistema notificará o profissional de saúde responsável pela criança internada.

## Funcionalidades

1) CRUDS:
	1) CRUD Profissional de saúde responsável;
	2) CRUD Responsável;
	3) CRUD Criança.
	
2) Implementação do PEWS com geração de relatórios frequentes;
2) Integração analógico/digital;
3) Sistema de notificação do profissional.

### Observações

* Para a integração analógico/digital, serão implementados circuitos de teste que simulam os sinais que seriam obtidos a partir de um sistema de monitoramento real. Além disso, a obtenção e processamento dos dados será realizada a partir de dispositivo microcontrolador programado em C/C++.