# fatec-cicd-gilson
Pipeline CI/CD desenvolvida para automatizar análise de segurança, testes e deploy utilizando GitHub Actions e CodeQL.

## Pipeline CI/CD

Este projeto utiliza GitHub Actions para orquestrar uma pipeline com análise de segurança via CodeQL, execução de testes automatizados com pytest e etapa de deploy para ambiente de staging, garantindo validação contínua do código antes da entrega.

## Evidências do Funcionamento

- Verde Inicial

![Pipeline Verde Inicial](<./Captura de tela 2026-05-24 145655.png>)
- Falha no Teste de Segurança
	![Pipeline Falha no Teste de Segurança](<./Captura de tela 2026-05-24 150120.png>)
- Verde após Correção
	![Pipeline Verde após Correção](<./Captura de tela 2026-05-24 150206.png>)

## Histórico de Commits

O histórico completo de commits está disponível na aba Commits do repositório e documenta a evolução do projeto entre implementação funcional, teste de segurança com falha esperada e correção final com retorno da pipeline ao estado verde.

## Nota Técnica

Durante a configuração do Advanced Setup do CodeQL, a interface do GitHub apresentou um alerta de possível redundância de configuração. Ainda assim, os logs da aba Actions confirmam que a análise de segurança foi executada com sucesso nas execuções da pipeline.

