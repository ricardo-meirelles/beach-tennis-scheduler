# 🎾 Beach Tennis Scheduler

![Status](https://img.shields.io/badge/Status-Em%20Produ%C3%A7%C3%A3o-success)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)
![JS](https://img.shields.io/badge/Frontend-JavaScript%20ES6-yellow)

Sistema inteligente de agendamento em tempo real desenvolvido para gestão de turmas de Beach Tennis nas cidades de **Fremont, Walnut Creek e Larkspur**.

## 🔗 Demonstração ao Vivo
Acesse a aplicação em produção: [https://beach-tennis-2852a.web.app](https://beach-tennis-2852a.web.app)

---

## 🚀 Funcionalidades Principais

- **Gestão de Níveis:** Filtros específicos para turmas Iniciantes, Intermediárias e Avançadas.
- **Geolocalização Dinâmica:** Seleção de cidades com integração automática ao Google Maps/Waze para cada quadra.
- **Smart Booking:** Sistema de 1ª, 2ª e 3ª opções de horário com gerenciamento automático de **Lista de Espera**.
- **Integração de Agenda:** Geração dinâmica de eventos para **Google Calendar** e arquivos **.ics** (Apple/Outlook).
- **Painel Administrativo:** Interface exclusiva para o professor gerenciar horários, editar aulas e alocar alunos da espera.
- **Segurança:** Autenticação via Firebase Auth com recuperação de senha por e-mail.

---

## 🛠️ Stack Tecnológica

- **Interface:** HTML5 e CSS3 com suporte nativo a Dark Mode.
- **Lógica:** JavaScript Vanilla (ES6+) consumindo Firebase SDK.
- **Banco de Dados:** Google Cloud Firestore (NoSQL) com índices compostos para ordenação de performance.
- **Hosting:** Firebase Hosting com deploy automatizado.

---

## 📊 Conexão com Data Science

Este projeto foi desenhado para servir como uma **fonte de extração de dados (ETL)** para análises futuras. A estrutura NoSQL do Firestore permite coletar:

1. **Análise de Demanda:** Identificação de horários de pico e cidades com maior engajamento.
2. **Perfil do Aluno:** Distribuição volumétrica por nível técnico.
3. **Otimização de Agenda:** Algoritmo simples de alocação de lista de espera que reduz a ociosidade das quadras.

> *Próximo passo do projeto: Desenvolver um Dashboard em Python (Streamlit/Pandas) para visualizar o Churn e a Retenção dos alunos mensais.*

---

## 👷 Como rodar o projeto localmente

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/beach-tennis-scheduler.git](https://github.com/SEU_USUARIO/beach-tennis-scheduler.git)

## 🤖 Metodologia de Desenvolvimento
Este projeto foi desenvolvido utilizando técnicas de **AI-Assisted Development**. Através do uso estratégico de IA Generativa, foi possível:
- Reduzir o tempo de prototipagem de semanas para dias.
- Implementar boas práticas de segurança e arquitetura NoSQL de forma ágil.
- Focar na lógica de negócios e na estrutura de dados, delegando a geração de boilerplate à inteligência artificial.