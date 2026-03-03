# Fabricação de PCB com xTool F1 Ultra usando Autodesk Fusion

## 📌 Visão Geral

Este tutorial descreve o processo completo para fabricação de placas de circuito impresso (PCB) utilizando a máquina **xTool F1 Ultra** em conjunto com o **Autodesk Fusion**.

O objetivo é demonstrar um fluxo prático para prototipagem rápida de PCBs por **gravação a laser**, desde o design até o acabamento final.

---

## 🛠️ Materiais Necessários

- Placa de cobre (fenolite)
- Máquina Laser xTool F1 Ultra
- Lixa fina ou esponja abrasiva

---

## 💻 Softwares Utilizados

- Autodesk Fusion (CAD/CAM)
- Inkscape (edição vetorial)
- Software da xTool (controle da máquina)

---

## 🔄 Fluxo do Processo

1. Exportação do circuito no Fusion (.PDF)
2. Conversão e ajuste no Inkscape (.SVG)
3. Configuração e gravação no xTool

---

## 📐 Etapa 1: Exportação do circuito no Fusion

Após finalizar o layout da PCB:

1. Selecione os layer a serem exportados
<div style="text-align: center;">
   <img src="imgs/0.png" style="width: 50%; height: auto;">
</div>

3. Clique em imprimir, deixa em eescala 1:1, selecione a opção **Black** e salve seu arquivo .pdf.

---

## 📤 Etapa 2: Preparação do arquivo no Inkscape

Abra o arquivo **.PDF** no Inkscape e siga:

1. Ajuste o tamanho da página para 
   - `Path → Object to Path`
2. Ajuste a escala se necessário (confira com régua)
3. Inverta cores se necessário
4. Remova elementos desnecessários
5. Exporte como **.SVG**

💡 Dica: use apenas preto (#000) para áreas que serão gravadas

---

## 🧩 Etapa 3: Configuração da máquina no xTool

1. Abra o software da xTool
2. Importe o arquivo **.SVG**
3. Configure:
   - Tipo: gravação (engrave)
   - Potência: ajustar conforme testes
   - Velocidade: depende do material

4. Posicione a placa corretamente
5. Faça um teste antes da execução final

---

## 🔩 Etapa 4: Finalizando

A xTool F1 Ultra **não é ideal para furação de PCBs**, então:

- Utilize furadeira de bancada **ou**
- Mini retífica (tipo Dremel)

Após isso:

- Lixe levemente a superfície
- Limpe com álcool isopropílico

---

## ✅ Resultado Esperado

![Resultado final](finalizado.png)

---
