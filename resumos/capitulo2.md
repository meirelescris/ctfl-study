# Capítulo 2 – Tipos e Níveis de Teste

## O que são níveis de teste
- *Unit (Unidade):* testa partes pequenas do código (funções, métodos).  
- *Integration (Integração):* testa interação entre módulos/componentes.  
- *System (Sistema):* testa o sistema como um todo.  
- *Acceptance (Aceitação):* valida com o cliente/usuário se atende aos requisitos.

## Tipos de teste (exemplos)
- *Funcionais:* verificam comportamento segundo requisitos (ex.: teste de login).  
  - Smoke / Sanity: checagem rápida se o sistema inicia.  
  - Regression: verificar se algo que já funcionava não quebrou.
- *Não-funcionais:* verificam qualidades (ex.: performance, segurança, usabilidade).  
  - Performance / Load / Stress  
  - Security (segurança)  
  - Compatibility (compatibilidade entre navegadores/dispositivos)

## Técnicas de design de teste
- *Caixa-preta:* testa funcionalidades sem olhar o código (ex.: equivalence partitioning, boundary values).  
- *Caixa-branca:* testa o código internamente (ex.: coverage, path testing).  
- *Caixa-cinza:* mistura das duas abordagens.

## Critérios e cobertura
- *Critério de saída (exit criteria):* quando os testes podem ser considerados concluídos (ex.: 95% de testes executados, zero defects críticos abertos).  
- *Cobertura:* quanto do código / requisitos foi testado (ex.: cobertura de requisitos / cobertura de código).

📌 Resumo rápido: entenda os *níveis* (unidade → integração → sistema → aceitação) e os *tipos* (funcionais x não-funcionais). Use técnicas apropriadas para cada caso.
