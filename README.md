# Inspeção SST por Câmera

Página de teste que usa uma webcam (ex.: Logitech Brio 500) ou fotos para analisar o ambiente de trabalho com o Claude e gerar:

- riscos com a NR aplicável e matriz de risco 5×5 (NR-01, GRO/PGR);
- avaliação 5S, pontos de melhoria (Kaizen, Poka-Yoke, gestão visual etc.);
- ciclo PDCA e plano de ação 5W2H;
- monitoramento automático em intervalos, com histórico e alerta sonoro de risco crítico.
- verificação de cada pessoa visível: riscos ocupacionais, EPIs faltando (NR-06) e adornos (NR-10, NR-12, NR-32);
- relatório técnico com capa, sumário, ferramentas da qualidade e plano de ação, baixado em Word (.docx), HTML ou PDF;
- câmeras: webcam USB/integrada, celular via QR code (fotos e áudios), Wi-Fi/IP (MJPEG, snapshot, HLS, MP4; RTSP via go2rtc);
- documentos e áudios do setor: a IA lê os documentos e transcreve os áudios (com a chave do Gemini).

## Como usar

1. Abra https://neltonsilva-sudo.github.io/inspecao-sst/ no Google Chrome. O link é sempre o mesmo: o `index.html` é um carregador que busca sempre a versão mais nova (`app.html`), sem cópia antiga do cache.
2. Cole uma chave do Google Gemini (gratuita, em aistudio.google.com/apikey) ou da Anthropic. A página reconhece pelo prefixo e a chave fica salva só no navegador.
3. Clique em **Ligar câmera**, escolha a câmera e em **Iniciar monitoramento** ou **Capturar quadro** + **Analisar ambiente**.

A análise por imagem apoia, mas não substitui, a inspeção de campo do profissional de SST. Projeto independente do simulador Germano–Ubu.
