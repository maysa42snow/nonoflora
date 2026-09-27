# 🌿 Catálogo Interativo de Venenos Vegetais

> **Trabalho de Campo:** Guia de Plantas Venenosas por Onde Passo
> **Disciplina:** Venenos Vegetais

---

## 📌 Sobre o Projeto

Este projeto consiste num catálogo interativo e educativo desenvolvido para mapear, identificar e analisar espécies vegetais com potencial tóxico encontradas em trajetos urbanos quotidianos (jardins, passeios, praças e canteiros públicos). 

A aplicação foi construída em página única (HTML/CSS/JS) e combina mapeamento geoespacial via satélite com uma ficha técnica detalhada de cada espécie, permitindo que a visualização seja feita tanto por ordem alfabética quanto por localização geográfica.

---

## 🎯 Objetivos

- Mapear e Catalogar: Identificar 10 espécies de plantas tóxicas/venenosas encontradas no trajeto quotidiano.
- Avaliação de Risco: Classificar o grau de toxicidade (escala de 1 a 5) e mapear os órgãos/tecidos vegetais de perigo.
- Educação e Prevenção: Apresentar os tipos de toxinas, mecanismos de ação fisiopatológica e sintomas de intoxicação humana e animal.
- Divulgação Científica: Reunir registos fotográficos próprios com coordenadas de campo numa ferramenta acessível.

---

## 🚀 Funcionalidades

- Mapeamento em Imagem de Satélite: Localização precisa de cada espécime via Leaflet e camadas da Esri World Imagery.
- Dupla Navegação:
  - Lista Alfabética: Seleção rápida por nome popular ou científico.
  - Interação no Mapa: Clique direto nos marcadores geográficos para focar no espécime.
- Ficha Técnica Lado a Lado:
  - Carrossel fotográfico automatizado com controlo de pausa ao passar o cursor e navegação manual por setas.
  - Painel com: Nome científico, parte tóxica, nível de toxicidade (1 a 5), mecanismo da toxina, características botânicas e referências bibliográficas.
- Transições Suaves: Animações dinâmicas que reorganizam a visualização entre visão geral e detalhes do espécime sem recarregar a página.

---

## 📂 Estrutura de Ficheiros

Para o correto funcionamento do catálogo, mantenha os ficheiros organizados na mesma pasta:

catalogo-plantas/

├── plantas.html           # Aplicação principal (HTML, CSS e JS)

├── README.txt             # Documentação do projeto

└── *.jpg                  # Registos fotográficos das espécies

---

## 🛠️ Tecnologias Utilizadas

- HTML5 & CSS3: Estruturação semântica, Flexbox e animações de transição.
- JavaScript (Vanilla): Controlo de estado, manipulação de DOM e lógica de carrossel.
- Leaflet.js: Biblioteca open-source para mapas interativos.
- Esri ArcGIS Tiles: Camada de imagens fotográficas de satélite em alta resolução.

---

## 🔬 Espécies Catalogadas

1. Avelós (Euphorbia tirucalli)
2. Espada-de-São-Jorge (Sansevieria trifasciata)
3. Trapoeraba-roxa / Coração-roxo (Tradescantia pallida)
4. Sangue-de-cristo (Euphorbia cotinifolia)
5. Acálifa / Folha-de-cobre (Acalypha wilkesiana)
6. Taioba-brava (Xanthosoma violaceum)
7. Chapéu-de-Napoleão (Thevetia peruviana)
8. Agave-dragão (Agave attenuata)
9. Figueira-benjamina (Ficus benjamina)
10. Moisés-no-berço (Tradescantia spathacea)

---

## ⚠️ Nota de Segurança e Metodologia

Aviso: Conforme as diretrizes pedagógicas da disciplina, não foi realizada recolha física de nenhum espécime vegetal. Todas as observações foram documentadas estritamente através de registos fotográficos digitais in situ, evitando o contacto direto com seivas cáusticas ou tecidos irritantes.
