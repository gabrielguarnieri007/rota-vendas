# 📱 Rota Vendas PWA

> Sistema de gestão de vendas e rotas georreferenciadas desenvolvido para otimizar o atendimento externo de representantes comerciais.

![Status](https://img.shields.io/badge/Status-Em_Produção-brightgreen) ![Version](https://img.shields.io/badge/Versão-74.0-blue)

## 🎯 Sobre o Projeto
O **Rota Vendas** é uma aplicação **PWA (Progressive Web App)** desenvolvida para resolver o problema de logística e emissão de pedidos em campo. O app permite cadastrar clientes via GPS, traçar rotas visuais em um mapa interativo e gerar pedidos em PDF com assinatura digital na hora, eliminando o uso de papel.

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5 & CSS3:** Interface moderna com Design System próprio e efeitos de Glassmorphism.
- **JavaScript (ES6+):** Lógica de SPA (Single Page Application) sem uso de frameworks pesados para máxima performance.
- **Leaflet API:** Renderização de mapas interativos com tiles customizados (CartoDB Light).

### Backend & Infraestrutura (Serverless)
- **Firebase Authentication:** Sistema de login seguro.
- **Cloud Firestore:** Banco de dados NoSQL em tempo real para sincronização de clientes e pedidos.
- **Firebase Hosting:** Hospedagem com certificado SSL e suporte a PWA.

### Bibliotecas Auxiliares
- **html2pdf.js:** Motor de renderização de PDFs direto no navegador.
- **Viewer.js:** Visualização avançada de imagens e comprovantes.

## ✨ Funcionalidades Principais

✅ **Geolocalização Inteligente:** Cadastro de clientes capturando a latitude/longitude exata via GPS do dispositivo.
✅ **Mapa Interativo:** Visualização de todos os clientes no mapa com pinos coloridos por status (Em aberto, Concluído, Sede).
✅ **Gestão de Pedidos:** Criação de pedidos com cálculo automático e geração de PDF profissional pronto para compartilhamento.
✅ **Assinatura Digital:** Captura de assinatura do cliente e do vendedor diretamente na tela do celular.
✅ **Modo PWA:** Instalável no Android/iOS, funcionando como um app nativo.

---
Desenvolvido por **Gabriel Guarnieri** 💻