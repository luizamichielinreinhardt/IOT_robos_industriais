# Robótica 4.0 — Catálogo Técnico de Robôs Industriais e IoT

Projeto acadêmico desenvolvido para a Unidade Curricular **Internet das Coisas**, do
Curso Técnico em Desenvolvimento de Sistemas — **SENAI Santa Catarina**.

Website responsivo, estático (HTML, CSS e JavaScript puros), apresentando os sete
principais modelos de robôs industriais utilizados na Indústria 4.0 e sua relação
com os conceitos e paradigmas da Internet das Coisas (IoT).

## 🔗 Demonstração

- **Site publicado (Vercel):** `<preencher após o deploy>`
- **Repositório (GitHub):** `<preencher com o link deste repositório>`

## 📁 Estrutura do projeto

```
robotica-iot/
├── index.html          # Página inicial — conceitos de IoT, robótica e automação
├── robos.html           # Catálogo com os 7 tipos de robôs industriais
├── css/
│   └── styles.css       # Sistema de design (tema "painel HMI industrial")
├── js/
│   ├── main.js          # Menu responsivo, relógio do painel, botão "voltar ao topo"
│   └── catalog.js        # Navegação por abas do catálogo de robôs
└── README.md
```

## 🧩 Conteúdo apresentado

**Página inicial (`index.html`)**
- Conceito de Internet das Coisas (IoT)
- Conceito de Robótica Industrial
- Importância da automação industrial
- Relação entre robótica e IoT (camadas de percepção, conectividade,
  processamento e atuação)

**Catálogo de robôs (`robos.html`)** — para cada um dos 7 modelos:

| # | Robô | Configuração cinemática |
|---|------|--------------------------|
| 01 | Cartesiano | 3 juntas prismáticas ortogonais (X, Y, Z) |
| 02 | SCARA | 2 juntas rotativas paralelas + curso Z + rotação da ferramenta |
| 03 | Articulado | Cadeia serial de 6 juntas rotativas |
| 04 | Cilíndrico | 1 junta rotativa + 2 juntas prismáticas |
| 05 | Delta | Manipulador paralelo suspenso (3 braços) |
| 06 | Polar | 2 juntas rotativas + 1 junta linear (coordenadas esféricas) |
| 07 | Colaborativo (Cobot) | Juntas com sensores de torque para operação segura com humanos |

Cada ficha traz: conceito, princípio de funcionamento, características técnicas,
aplicações industriais, integração com automação/IoT e três modelos comerciais de
fabricantes distintos.

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (variáveis/custom properties, grid e flexbox, responsivo mobile-first)
- JavaScript puro (sem frameworks/bibliotecas externas)
- Ilustrações e diagramas cinemáticos em SVG (autorais, sem uso de imagens de terceiros)

## ▶️ Como executar localmente

Não há build nem dependências. Basta abrir `index.html` no navegador, ou servir a
pasta com qualquer servidor estático, por exemplo:

```bash
python3 -m http.server 8000
# acessar http://localhost:8000
```

## 🚀 Publicação no GitHub e Vercel

1. Criar um repositório no GitHub e enviar todos os arquivos deste projeto.
2. Em [vercel.com](https://vercel.com), importar o repositório.
3. Como é um site estático (sem *framework*), selecionar **Other** como
   *Framework Preset* e manter o diretório raiz — não é necessário comando de build.
4. Publicar e copiar o link gerado para a seção de entregas da avaliação.

## 📚 Fontes técnicas consultadas

As especificações e modelos comerciais citados foram baseados em documentação
pública dos fabricantes (FANUC, ABB, KUKA, Yaskawa, Epson/Seiko Epson, Yamaha
Motor, IAI Corporation, Bosch Rexroth, Universal Robots, Omron, Prab, Kawasaki
Heavy Industries, entre outros) e em literatura consolidada de robótica industrial.

