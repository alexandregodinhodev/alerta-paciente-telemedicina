# Alerta de Paciente para Telemedicina

Extensão para Google Chrome que toca um alerta sonoro quando um paciente
entra na sala de espera do portal de teleconsulta, permitindo que o
profissional se ausente do computador sem perder atendimentos.

## O problema

Médicos em regime home office precisam acompanhar a tela o tempo todo
para perceber quando um paciente está aguardando. Isso atrapalha a
rotina e pode gerar atrasos no atendimento.

## A solução

A extensão monitora a página a cada 2 segundos, detecta a presença de
paciente aguardando, destaca o card na tela e dispara um alarme sonoro
uma única vez por novo paciente.

## Funcionalidades

- Detecção automática de paciente aguardando
- Alarme sonoro sem repetição indevida
- Destaque visual do card na tela
- Funcionamento em segundo plano, sem interação do usuário

## Tecnologias

- JavaScript
- Chrome Extensions API (Manifest V3)
- Content Scripts e Web Accessible Resources

## Resultado

Desenvolvido para uso real na rotina de uma médica de telemedicina,
ajudando a reduzir o tempo de espera dos pacientes.

## Próximos passos

- Botão para silenciar ou ajustar o volume do alarme
- Notificação do navegador além do som

## Código-fonte

O código é mantido em repositório privado e está disponível para
demonstração mediante contato.

## Autor

**Alexandre Godinho**
(https://linkedin.com/in/alexandre-godinho-dev/) | alexandre-godinho@live.com
