# 🏭 Dashboard Operacional de Bobinas
https://marcus7170.github.io/DEC3/

Um sistema web inteligente desenvolvido para facilitar os cálculos dimensionais de bobinas de aço, padronizar a geração de mensagens operacionais (LTF, LI's, BF-N e BQD) e agilizar a consulta de normas no chão de fábrica.

## 🚀 Funcionalidades Principais

- **Geradores de Mensagem (BF-N e BQD):** Criação rápida e padronizada de relatórios de inspeção, permitindo adicionar múltiplos defeitos, informar medições (Raio Gama/Side Trimmer) e registrar a equipe operacional.
- **Dicionário de Códigos (Novo):** Aba dedicada para consulta rápida com filtro em tempo real de Códigos, Abreviações e Descrições de defeitos laminados, além de tabelas de apoio (Equipamentos, Localização e Intensidade).
- **Cálculo Bidirecional:** Encontre a posição exata do defeito calculando pela **Metragem** ou pelo **Peso**.
- **Cálculo Automático de Coroa:** O sistema utiliza a fórmula de área circular para definir a posição da coroa (mm) em tempo real, sem necessidade de digitação manual.
- **Gerador de Alertas Inteligente:** Cria textos padronizados com concordância gramatical automática (ex: "NA FACE", "NO CENTRO", "NAS BORDAS") e formatação correta de unidades.
- **Informativos Operacionais:** Acesso rápido a resumos de rotinas e normas (ex: Rotinas Decapagem 3) direto na interface via Modal.
- **UI/UX Moderna:** Interface responsiva com suporte a **Dark Mode** e **Light Mode**, além de botões de cópia rápida (Copy to Clipboard).

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica.
- **CSS3:** Estilização com variáveis para temas nativos (Dark/Light).
- **JavaScript (Vanilla):** Lógica matemática de engenharia reversa, sistema de busca/filtros e manipulação do DOM em tempo real. Não requer frameworks ou banco de dados externo.

## ⚙️ Como Usar

O projeto é 100% *client-side* (roda direto no navegador).

1. Acesse o link do projeto ou baixe o arquivo `.html` deste repositório.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador de internet (Chrome, Edge, Firefox).
3. Selecione a operação desejada no menu principal (Geradores, Cálculos ou Consulta de Códigos), preencha os dados e copie suas mensagens!

## 👨‍💻 Autor

Criado por **Marcus V. Soares da Silva** (U012697).  
*Projeto experimental, voluntário e voltado exclusivamente para fins não lucrativos e ganho de produtividade.*
