# Projeto NeoADP

## Sobre

Este projeto tem como objetivo principal a implementação do método PEWS, uma ferramenta de uso dos profissionais da saúde que, com base no estado de uma criança, calcula uma intervenção a partir de um sistema de pontuações. Em outras palavras, esta ferramenta entrega uma solução específica para um(a) menino(a) que apresente determinados sintomas, o que agiliza o processo de diagnóstico e, consequentemente, de tratamento.

## Funcionalidades

1) CRUDS:
	1) CRUD Profissional de saúde responsável;
	2) CRUD Responsável;
	3) CRUD Criança;
	4) CRUD Internação.
	
2) Implementação do PEWS;
2) Integração analógico/digital ¹;
3) Sistema de notificação do profissional.

### Observações

* ¹ Para a integração analógico/digital, serão implementados circuitos de teste que simulam os sinais que seriam obtidos a partir de um sistema de monitoramento real. Além disso, a obtenção e processamento dos dados será realizada a partir de dispositivo microcontrolador programado em C/C++.

## Anotações para os participantes do projeto

### 20/12/2024 - Juliano

* O back-end muito provavelmente será todo feito em Django (Python), pra facilitar no desenvolvimento e agilizar o processo, já que a linguagem é de mais alto nível;
* É interessante manter algumas funcionalidades mais simples em JavaScript mesmo, como o cáculo da soma dos sintomas e a assimilação à intervenção necessária;
* A ferramenta pode ser utilizada sem a identificação do profissional (login) e da criança. Contudo, para registrar um relatório no banco de dados, é obrigatório o login e a identificação da criança por meio do protocolo de internação (olhar o modelo conceitual do banco de dados, vulgo arquivo '.mwb');
* Não tenho certeza ainda de como funcionará os tipos de cadastro; por quem será cadastrada a criança, por quem será cadastrado o profissional responsável, etc. Mas, por ora, poderia ser feito sem qualquer validação, para simplificar, e implementamos validação conforme necessário.