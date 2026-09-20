# Geotag & EXIF Studio 🛰️📸

Aplicação web desenvolvida para uso em campo e em escritório, projetada para **extrair automaticamente metadados EXIF/GPS de imagens JPEG** (como coordenadas de latitude, longitude, altitude, data e modelo do drone/câmera) e sobrepô-los de forma visível e personalizada na própria imagem, junto com um logotipo institucional e textos customizados.

O grande diferencial: **funciona 100% offline** em um único arquivo, garantindo total privacidade e autonomia em missões de campo sem acesso à internet.

---

## ✨ Principais Recursos

- **Processamento 100% Offline:** Arquivo único contendo toda a lógica e estilos. Baixe uma vez e rode direto no navegador do computador, tablet ou celular.
- **Leitura Automática de EXIF & GPS:** Decodificação nativa de coordenadas geográficas, altitude, carimbo de data/hora e identificação do equipamento (marca e modelo de câmeras e drones, como linhas DJI).
- **Personalização de Textos:** Edição livre do modelo do equipamento, inclusão de textos adicionais (ex: nome do projeto, setor, local) e ativação/desativação modular de elementos.
- **Logotipo e Alinhamentos Independentes:** Insira sua logo e posicione textos e logotipos de forma isolada na parte inferior da imagem (**Esquerda, Centro ou Direita**).
- **Estilos Visuais Avançados:** Controles de tamanho de fonte, opacidade da tarja de fundo, cor do texto e escala da logo em tempo real.
- **Exportação em Alta Resolução:** Pré-visualização instantânea e download da imagem final tratada mantendo a qualidade original.

---

## 🚀 Como Usar (Modo Offline)

1. Faça o download do arquivo [index.html](index.html) deste repositório.
2. Salve-o em seu computador, tablet ou smartphone.
3. Dê um duplo clique no arquivo (ou abra-o diretamente em qualquer navegador moderno como Chrome, Edge ou Safari). O aplicativo funcionará imediatamente, mesmo sem internet.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** com design responsivo estilizado via **Tailwind CSS**.
- **JavaScript Moderno (ES6+)** para manipulação de arquivos locais, leitura de headers binários EXIF e renderização via HTML5 Canvas.

---

## 📜 Licença

Este projeto é distribuído sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
