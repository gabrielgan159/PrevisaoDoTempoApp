# PrevisaoDoTempoApp
# ☀️ App de Previsão do Tempo - APO Programação de Dispositivos Móveis

Este projeto foi desenvolvido como Atividade Prática Orientada (APO) para a disciplina de Programação de Dispositivos Móveis da UNIPAR EAD.

O aplicativo simula um app de previsão do tempo, atendendo a todos os requisitos solicitados, com foco na integração de componentes nativos do Android e consumo de API.

## 🛠️ Tecnologias e Componentes Utilizados

| Categoria | Componentes / Linguagens |
| :--- | :--- |
| **Linguagem** | Java |
| **Arquitetura** | Multi-Activity (Splash, Main, Sobre) e Fragments (Previsão, Mapa) |
| **Design/Layout** | Material Design, RecyclerView e CardView |
| **Navegação** | Toolbar, TabLayout com ViewPager2, Menu na AppBar |
| **Rede (API)** | Retrofit 2.9 (usado para consumir a API da HG Brasil) |
| **Funcionalidade Extra** | Zxing (usado para Escaneamento de QR Code no FAB) |

## 🗺️ Requisitos de Telas e Funcionalidades

Todos os requisitos da APO foram implementados:

* **Splash Screen:** Executada por 3 segundos com `Handler`.
* **Aba Previsão (Fragment):** Lista de previsão do tempo obtida da API da HG Brasil, exibida em `RecyclerView` com `CardView`.
* **Aba Mapa (Fragment):** Simulação da tela de mapa. *A funcionalidade interativa foi simulada devido à exigência de verificação de pagamento para a API do Google Maps.*
* **Menu/Tela "Sobre":** Menu na `Toolbar` que abre uma Activity separada com dados pessoais (Nome, RA, Curso).
* **FAB (Floating Action Button):** Botão para iniciar o Escaneamento de QR Code via biblioteca Zxing.
