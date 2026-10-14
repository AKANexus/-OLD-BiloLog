# BiloLog

**Projeto histórico — sem manutenção ativa.** Este repositório é preservado como registro de uma etapa anterior de desenvolvimento. Não há previsão de novas funcionalidades ou correções.

## Sobre o projeto

Aplicativo móvel em Flutter para operações logísticas envolvendo remessas e pacotes. Substitui-se aqui o README padrão do Flutter por uma descrição do escopo efetivamente presente no repositório.

## Escopo preservado

O aplicativo contém autenticação, listagem e criação de remessas, consulta de pacotes, leitura de QR codes e entrada manual de códigos. As rotinas de entrega enviam informações do recebedor, localização, observações e fotografias para uma API, além de registrar problemas na entrega.

## Tecnologias e organização

Flutter e Dart, com faixa de SDK declarada como `>=2.16.0 <3.0.0`. Utiliza Provider, HTTP, câmera, mobile_scanner e localização; `lib/models/`, `lib/providers/`, `lib/views/` e `lib/widgets/` separam dados, comunicação, telas e componentes.

## Estado e contexto de execução

O aplicativo depende de uma API externa e das permissões de câmera e localização do dispositivo. O repositório do cliente móvel, isoladamente, não fornece o backend necessário para reproduzir o fluxo completo de operação.

Esta documentação foi revisada a partir dos arquivos versionados. Não foram executados build, testes funcionais ou integrações durante a revisão; as versões citadas descrevem o projeto preservado, não uma recomendação de stack para novos sistemas.
