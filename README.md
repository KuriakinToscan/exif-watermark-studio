# Geotag & EXIF Studio 🛰️📸 (v2.0)

Aplicação web avançada desenvolvida para uso em campo e em escritório, projetada para **extrair automaticamente metadados EXIF/GPS e telemetria de imagens JPEG** (com suporte otimizado para drones DJI e câmeras gerais), sobrepõem coordenadas, modelo do equipamento, data, altitude e a **direção de azimute com seta indicativa**, além de logotipos personalizados.

Tudo isso rodando **100% offline em um único arquivo**, com suporte completo a **processamento em lote (Batch)** e exportação compactada em **ZIP**.

---

## ✨ Principais Recursos da Versão 2.0

- **Processamento em Lote (Batch & Pastas):** Selecione múltiplos arquivos JPEG ou aponte para uma pasta inteira no seu computador para processar centenas de fotos de uma só vez.
- **Exportação Automatizada em ZIP:** Compacta e baixa todas as imagens processadas em alta resolução instantaneamente em um único arquivo `.zip`.
- **Processamento 100% Offline:** Arquivo único contendo toda a lógica, bibliotecas e estilos. Baixe uma vez e rode direto no navegador sem depender de internet.
- **Leitura Inteligente de EXIF, GPS & DJI:** Decodificação de latitude, longitude, altitude, carimbo de data/hora e identificação refinada de modelos de drones e câmeras (linhas DJI Mavic, Air, Mini, Matrice, Zenmuse, além de smartphones e outras marcas).
- **Indicador Dinâmico de Azimute (Direção):** Extração da tag de orientação de campo (`GPSImgDirection`) acompanhada de uma **seta vetorial rotacionada em tempo real** apontando para a direção da tomada em relação ao norte.
- **Logotipo no Topo e Textos na Base:** Layout limpo com alinhamentos independentes (Esquerda, Centro ou Direita) fixados de forma inteligente.
- **Controles Visuais Independentes:** Ajustes de escala de fonte, tamanho do logotipo, cor unificada de fundo e **opacidades totalmente separadas** para o texto, para o fundo do texto e para o fundo do logotipo.

---

## 🚀 Como Usar

1. Faça o download do arquivo [index.html](index.html) desta versão 2.0 no repositório.
2. Salve-o em seu computador, tablet ou smartphone.
3. Dê um duplo clique para abrir o arquivo em qualquer navegador moderno (Chrome, Edge, Safari, Firefox). O aplicativo funcionará imediatamente de forma totalmente isolada e offline.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** com design responsivo estilizado via **Tailwind CSS**.
- **JavaScript Moderno (ES6+)** para manipulação local, leitura de headers binários EXIF e renderização via HTML5 Canvas.
- **EXIF-JS** e **JSZip** integrados para manipulação de metadados e empacotamento em lote.

---

## 📜 Licença

Este projeto é distribuído sob os termos da licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
