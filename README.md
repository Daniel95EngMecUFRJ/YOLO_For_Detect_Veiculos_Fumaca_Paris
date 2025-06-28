# YOLO_For_Detect_Veiculos_Fumaca_Paris

# YOLOv8: Detecção de Veículos e Emissão de Fumaça
Este notebook aplica o modelo YOLOv8 pré-treinado para detectar veículos e analisar visualmente a emissão de fumaça em imagens urbanas, simulando a identificação de fontes poluentes para fins ambientais.

## Etapas:
1. Instalação do Ultralytics
2. Upload da imagem com emissão de fumaça
3. Inferência com YOLOv8
4. Visualização e contagem de veículos
Detectar veículos e identificar aqueles emitindo fumaça preta (indicando alta emissão de poluentes), com contagem automática.

🧠 Como vamos fazer isso?

🔧 Tecnologias e bibliotecas
Ultralytics YOLOv8 (ou YOLOv9 se disponível)

Dataset com veículos e fumaça → usaremos imagens reais e/ou geradas por IA.

Treinamento customizado (se necessário, com poucas imagens rotuladas).

Contagem baseada na classe detectada (ex: "car" vs. "car+smoke").

🚀 PLANO DE AÇÃO PARA O CÓDIGO

ETAPA 1 — Preparar o ambiente (Google Colab)
Instalar Ultralytics

Fazer upload de imagens de teste com veículos emitindo fumaça

Rodar o YOLO pré-treinado para detecção de veículos

Aplicar segmentação (YOLOv8-seg) para verificar contornos da fumaça 
