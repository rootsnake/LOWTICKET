<div align="center">
  <h1>🔥 VSL High-Conversion Page</h1>
  <p><b>Página de vendas estática otimizada para máxima conversão e carregamento instantâneo.</b></p>

  <!-- Badges de Status -->
  <img src="https://img.shields.io/badge/Status-No%20Ar-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Performance-100%20Optimized-blue?style=for-the-badge" alt="Performance">
  <img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-orange?style=for-the-badge&logo=githubactions" alt="CI/CD">
</div>

<br>

---

## 🎬 Sobre o Projeto
Landing page de alta conversão estruturada especificamente para exibição de **VSL (Video Sales Letter)**. Focada em velocidade de carregamento (*Core Web Vitals*), design limpo e experiência sem distrações para reter a atenção do lead até a chamada para ação (CTA).

---

## 🏗️ Arquitetura da Página
Como a estrutura é focada em velocidade, o fluxo de entrega do conteúdo visual é direto ao ponto:

```mermaid
graph TD
    User([Visitante / Lead]) -->|HTTPS / CDN| Page[Página Estática HTML/CSS/JS]
    Page -->|Stream de Vídeo| VSL[Player de VSL Otimizado]
    Page -->|Clique na CTA| Checkout[Página de Pagamento / Gateway]