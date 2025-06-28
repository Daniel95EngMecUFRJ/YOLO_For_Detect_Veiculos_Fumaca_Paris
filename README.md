# YOLO_For_Detect_Veiculos_Fumaca_Paris
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
