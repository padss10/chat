# Assistente Didático para Investidores Iniciantes

O chat é um protótipo de assistente virtual baseado em Inteligência Artificial (IA) desenvolvido para ajudar novos investidores a darem seus primeiros passos no mercado financeiro. Ele atua como um educador financeiro de bolso, traduzindo o "economês" para uma linguagem simples, acolhedora e acessível, usando analogias práticas do dia a dia.

Este projeto foi construído seguindo rigorosas diretrizes de segurança regulatória do mercado financeiro, garantindo que o agente atue *apenas de forma educacional*, sem realizar recomendações diretas de compra ou venda de ativos.

---

##  Público-Alvo e Objetivos

* Público-Alvo: Clientes recém-cadastrados na corretora, pessoas sem experiência prévia em investimentos ou que possuem medo de perder dinheiro.
* Objetivo Principal: Reduzir a barreira de entrada no mercado financeiro, educando o usuário sobre conceitos básicos (Renda Fixa, Renda Variável, Reserva de Emergência) e ajudando-o a tomar a próxima decisão de aprendizado com confiança.

---

# Funcionalidades e Diferenciais

* Confinamento de Conhecimento (RAG): O assistente responde perguntas com base estrita em uma base de dados local (`base_conhecimento.txt`), evitando alucinações sobre dados externos ou desatualizados.
* Blindagem de Segurança (Guardrails): Implementação de travas no prompt de sistema que impedem o agente de fazer recomendações de investimentos ou prometer rentabilidade garantida.
* Tom Empático e Didático: O robô valida os medos naturais do investidor iniciante e explica os conceitos utilizando analogias simples (como comparar o risco com um tripé de sustentação).

---

# Estrutura do Projeto

O repositório está organizado da seguinte forma:

```text
├── base_conhecimento.txt   # Dados técnicos sobre investimentos (Renda Fixa, Variável, Perfis)
├── main.py                 # Código principal em Python (integração com a API de IA)
├── requirements.txt        # Dependências do projeto para instalação rápida
└── README.md               # Documentação completa do projeto
# chat