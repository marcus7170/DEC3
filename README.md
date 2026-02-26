# 🏭 Dashboard Operacional de Bobinas
https://marcus7170.github.io/DEC3/
Um sistema web inteligente desenvolvido para facilitar os cálculos dimensionais de bobinas de aço e padronizar a geração de mensagens de alerta operacionais (LTF e LI's) no chão de fábrica.

## 🚀 Funcionalidades Principais

- **Cálculo Bidirecional:** Encontre a posição exata do defeito calculando pela **Metragem** ou pelo **Peso**.
- **Cálculo Automático de Coroa:** O sistema utiliza a fórmula de área circular para definir a posição da coroa (mm) em tempo real, sem necessidade de digitação manual.
- **Gerador de Alertas Inteligente:** Cria textos padronizados para LTF e LI's com concordância gramatical automática (ex: "NA FACE", "NO CENTRO", "NAS BORDAS") e formatação correta de unidades (`mm` minúsculo).
- **Auto-completar de Defeitos:** Banco de dados integrado com dezenas de códigos e descrições (ex: *A1 - AMASSAMENTO*), filtrando a saída na mensagem final.
- **UI/UX Moderna:** Interface responsiva com suporte a **Dark Mode** e **Light Mode**, além de botões de cópia rápida (Copy to Clipboard).

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica.
- **CSS3:** Estilização com variáveis para temas nativos (Dark/Light).
- **JavaScript (Vanilla):** Lógica matemática de engenharia reversa e manipulação do DOM em tempo real. Não requer frameworks.

## ⚙️ Como Usar

O projeto é 100% *client-side* (roda direto no navegador).

1. Faça o clone deste repositório ou baixe o arquivo `.html`.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador de internet (Chrome, Edge, Firefox).
3. Selecione a aba desejada (Metragem ou Peso), preencha os dados e copie suas mensagens!

## 👨‍💻 Autor

Criado por **Marcus V. Soares da Silva** (U012697).  
*Projeto experimental, voluntário e voltado exclusivamente para fins não lucrativos e ganho de produtividade.*
