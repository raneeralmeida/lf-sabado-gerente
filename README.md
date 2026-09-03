# ⚽ Gerente LF Sábado | PWA de Gestão Esportiva

👉 [ACESSAR O APLICATIVO ONLINE](COLOQUE_SEU_LINK_DO_GITHUB_PAGES_AQUI)

Uma aplicação Web Progressiva (PWA) desenvolvida do zero para automatizar, organizar e gerenciar partidas de futebol amador. O projeto substitui o tradicional "caderninho" por um sistema inteligente, rápido e projetado para a usabilidade à beira da quadra.

---

## 🚀 Principais Funcionalidades e Soluções Técnicas

Este projeto foi construído focando na resolução de problemas reais de uso de dispositivos móveis em ambientes externos, aplicando conceitos sólidos de engenharia de front-end:

* **Sorteio Cego (Fisher-Yates):** Implementação de um algoritmo de duplo embaralhamento (Double Shuffle) para garantir equipes formadas de maneira 100% planejada e imparcial, com separação prévia de goleiros.
* **Lógica de Partida Automática (Auto-End):** O sistema monitora a partida em background aplicando as regras do jogo. A partida encerra automaticamente e bloqueia novos eventos se o cronômetro zerar, um único jogador marcar 2 gols, ou a partida atingir um limite global de 3 gols, agilizando a rotação na quadra.
* **Recuperação de Estado (Anti-Zumbi):** Uso intensivo da API `localStorage` para criar backups contínuos e automáticos do estado da aplicação. Se o navegador do celular encerrar a página por falta de memória RAM, o usuário retornará exatamente de onde parou.
* **UI Glassmorphism e Tela Única (Compactação):** Interface redesenhada sob o conceito de "vidro fosco" (Glassmorphism escuro). O design foca na ação beira-quadra: o placar tradicional numérico foi removido em favor de um cronômetro de alto contraste e um botão de ação global ("Marcar Gol"), eliminando o scroll e acelerando o input.
* **API Screen Wake Lock:** Integração com a API nativa do navegador para evitar que a tela do dispositivo bloqueie ou desligue enquanto o cronômetro da partida estiver em andamento.
* **Gestão Dinâmica de Equipes:** Regras de negócio flexíveis que permitem adicionar "atrasildos" (jogadores que chegam após o sorteio) diretamente para a fila, além de substituições manuais avançadas nos times já formados.
* **Integração e Compartilhamento:** Uso da `clipboard API` para gerar e exportar relatórios formatados (escalações e documentação de artilharia) diretamente para o WhatsApp.
* **PWA Completo:** Arquitetura Progressive Web App configurada com `manifest.json`, Service Workers (`sw.js`) com injeção de cache e banner de instalação nativo, permitindo o funcionamento 100% offline.

---

## 💻 Tecnologias Utilizadas

* **HTML5** (Semântico e acessível)
* **Tailwind CSS** (Estilização utilitária, responsividade extrema e design system)
* **JavaScript Vanilla (ES6+)** (Lógica de negócio, algoritmos de sorteio, manipulação de DOM)
* **APIs da Web:** `Service Workers`, `Wake Lock API`, `Clipboard API`, `Web Storage API`

---

## 📱 Como testar o aplicativo

1. Acesse o link oficial: [LF Sábado Manager](COLOQUE_SEU_LINK_DO_GITHUB_PAGES_AQUI)
2. **No Computador:** Pressione `F12` e ative a visualização de dispositivos móveis (Device Toolbar) para uma experiência ideal.
3. **No Celular:** Abra o link pelo navegador (Chrome/Safari). Uma notificação de instalação do aplicativo surgirá após alguns segundos. Ao instalar, o aplicativo passa a rodar em tela cheia e sem depender de internet.

---

## 👨‍💻 Autor

Desenvolvido por **Râneer Almeida**.

* **LinkedIn:** [linkedin.com/in/raneer-antonio-de-almeida](https://www.linkedin.com/in/raneer-antonio-de-almeida)
* Projeto criado para portfólio de transição de carreira para a área de Análise e Desenvolvimento de Sistemas.
