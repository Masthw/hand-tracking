# 🖐 Hand Tracker

Um projeto em **Python** que utiliza **MediaPipe** e **OpenCV** para detectar mãos em tempo real pela webcam. Permite visualizar a detecção de mãos e os pontos de articulação (landmarks), mostrando também o FPS da câmera.

---

## 🛠 Tecnologias

- **Python 3.10+**
- **OpenCV**: captura e exibição de vídeo
- **MediaPipe**: detecção e rastreamento de mãos
- **NumPy**: manipulação de arrays (compatível com MediaPipe)

---

## 🚀 Como rodar

1. Clonar o repositório:

```bash
git clone https://github.com/SEU-USUARIO/meu-projeto.git
cd meu-projeto
```

2. Criar e ativar o ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows
```

3. Instalar dependências:

```bash
pip install -r requirements.txt
```

4. Rodar o script:

```bash
python HandTrackingModule.py
```

---

### ⚡ Observações

---

- Funciona melhor em ambientes com boa iluminação.
- FPS depende da webcam e do computador.
- Para projetos que combinam MediaPipe + OpenCV, mantenha as versões travadas: 
 
```bash
numpy<2
opencv-python<4.11
mediapipe==0.10.21
```
