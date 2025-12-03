# ☀️ SolarFlow Pro Calculator

Uma aplicação web robusta para dimensionamento de sistemas fotovoltaicos, focada em precisão de engenharia e usabilidade para integradores solares.

![Status](https://img.shields.io/badge/Status-Production%20Ready-green)
![Tech](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-blue)

## 🚀 Funcionalidades

- **Geolocalização Automática:** Integração com Nominatim (OSM) e API nativa do navegador.
- **Dados Climáticos Reais:** Busca automática de irradiação (HSP) baseada no histórico anual do local via Open-Meteo API.
- **Dimensionamento Inteligente:**
  - Cálculo de Módulos e Potência Pico.
  - Seleção automática de Inversor Comercial (Banco de dados de potências reais).
  - Análise de Overload (FDI) com alertas de Clipping.
- **Personalização (White Label):** Integradores podem inserir nome da empresa e WhatsApp, salvos localmente no navegador.
- **Exportação:** Geração de relatórios em PDF formatados e envio direto via WhatsApp.

## 🛠️ Como Usar

1. Clone o repositório ou baixe o arquivo `index.html`.
2. Abra em qualquer navegador moderno.
3. Digite a cidade ou use o botão de GPS.
4. Ajuste consumo e potência do painel.
5. Obtenha o relatório técnico instantâneo.

## 📦 Deploy (Como colocar no ar)

A maneira mais fácil é usar o **GitHub Pages**:

1. Crie um repositório no GitHub.
2. Faça o upload do arquivo `index.html`.
3. Vá em **Settings** > **Pages**.
4. Em "Source", selecione `main` (ou `master`) e salve.
5. Seu site estará online em `https://seu-usuario.github.io/seu-repositorio`.

## 🔒 Licença

Desenvolvido para **SolarFlow Pro**.
Todos os direitos reservados sobre a lógica de dimensionamento proprietária.

---
*Feito com ⚡ por SolarFlow Engineering.*