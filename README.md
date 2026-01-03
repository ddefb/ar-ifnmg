# IFNMG-AR — Realidade Aumentada no Ensino Médio Integrado
Este repositório contém o protótipo de Realidade Aumentada (RA) desenvolvido como parte do estudo: [_"Realidade aumentada como ferramenta complementar ao ensino: um estudo de caso aplicado ao Ensino Médio Integrado do IFNMG – Campus Arinos."_](https://doi.org/10.46636/recital.v7i2.741)

O projeto utiliza A-Frame e AR.js para criar experiências educacionais baseadas em marcadores físicos, permitindo a visualização de modelos 3D diretamente no navegador, sem necessidade de instalação de aplicativos.

## Objetivos
O objetivo principal é avaliar o uso da Realidade Aumentada como ferramenta pedagógica complementar, promovendo:

- maior engajamento dos estudantes,
- melhor assimilação de conteúdos abstratos,
- experimentação prática de tecnologias emergentes,
- integração entre ensino de computação e visualização interativa.

O projeto foi aplicado no Ensino Médio Integrado do IFNMG – Campus Arinos, no contexto de uma metodologia de pesquisa-ação.

## Como Executar o Projeto

O projeto está disponível online e não requer instalação.

### Passo 1 — Acesse o link
Abra o navegador e acesse: [https://ddefb.github.io/ar-ifnmg/](https://ddefb.github.io/ar-ifnmg/)

### Passo 2 — Autorize o uso da câmera
Quando solicitado pelo navegador, permita o acesso à câmera do dispositivo.

> Importante! Sem a permissão da câmera, a Realidade Aumentada não será ativada.

### Passo 3 — Prepare os marcadores
Utilize os marcadores disponíveis na pasta [`/marker`](marker/) do repositório.
Os marcadores podem ser:
- impressos em papel, ou
- exibidos em outro dispositivo (celular, tablet ou monitor).

### Passo 4 — Aponte a câmera para o marcador
Aponte a câmera para o marcador, mantendo uma distância aproximada de 20–40 cm e boa iluminação.

### Passo 5 — Visualize e interaja
Ao reconhecer o marcador, o modelo 3D será exibido automaticamente na tela.
Mova o marcador ou a câmera para explorar o objeto em diferentes ângulos.


## Tecnologias Utilizadas

- A-Frame — framework WebXR para construção de cenas 3D em HTML
- AR.js — biblioteca de Realidade Aumentada baseada em marcadores
- ARToolkit markers — reconhecimento de padrões visuais
- GLTF / BIN — modelos tridimensionais
- HTML + JavaScript

## Como citar este trabalho

If you use this repository in your work, please cite the corresponding publication:

```BibTeX
    @article{PeixotoMartinsBezerra2025,
      title   = {Realidade aumentada como ferramenta complementar ao ensino: um estudo de caso aplicado ao Ensino Médio Integrado do IFNMG -- Campus Arinos},
      author  = {Peixoto, Luara Brito and Martins, Danilo Silveira and Bezerra, Diego de Freitas},
      journal = {Recital -- Revista de Educação, Ciência e Tecnologia de Almenara/MG},
      volume  = {7},
      number  = {2},
      pages   = {412--431},
      year    = {2025},
      month   = dec,
      doi     = {10.46636/recital.v7i2.741},
      url     = {https://recital.almenara.ifnmg.edu.br/recital/article/view/741}
    }
```

```txt
PEIXOTO, Luara Brito; MARTINS, Danilo Silveira; BEZERRA, Diego de Freitas. Realidade aumentada como ferramenta complementar ao ensino: um estudo de caso aplicado ao Ensino Médio Integrado do IFNMG – Campus Arinos. Recital - Revista de Educação, Ciência e Tecnologia de Almenara/MG, [S. l.], v. 7, n. 2, p. 412–431, 2025. DOI: 10.46636/recital.v7i2.741. Disponível em: https://recital.almenara.ifnmg.edu.br/recital/article/view/741. Acesso em: 3 jan. 2026.
```

## Licença

Este projeto é disponibilizado exclusivamente para fins educacionais e acadêmicos.

