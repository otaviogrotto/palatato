# Palatato | ODS 3: Saúde e Bem-Estar

## 📖 Sobre o Projeto
O **Palatato** é uma aplicação web desenvolvida como proposta de intervenção tecnológica para o **Objetivo de Desenvolvimento Sustentável (ODS) 3 da ONU**. O sistema realiza o cálculo do metabolismo basal e do gasto calórico diário, fornecendo sugestões qualitativas de refeições saudáveis de acordo com o objetivo do usuário (emagrecimento, manutenção ou ganho de massa). 

O foco é democratizar a informação nutricional básica e auxiliar na prevenção de doenças crônicas não transmissíveis através da educação alimentar.

## ⚙️ Funcionalidades
- Coleta de dados antropométricos (peso, altura, idade, sexo e nível de atividade).
- Cálculo automático da Taxa de Metabolismo Basal (TMB) via fórmula de Harris-Benedict.
- Projeção do Gasto Energético Total (GET).
- Exibição de cardápios qualitativos baseados no objetivo selecionado.
- Interface responsiva (Mobile-first).

## 🎨 Paleta de Cores

A paleta foi pensada para transmitir confiança, saúde e naturalidade — valores diretamente ligados ao tema de alimentação saudável e bem-estar.

| Nome              | Hex       | Papel                                              |
|-------------------|-----------|----------------------------------------------------|
| Verde musgo       | `#3d7a4f` | Cor primária — identidade visual principal         |
| Verde escuro      | `#2b5737` | Hover, contrastes e elementos de ênfase            |
| Verde suave       | `#e8f5ec` | Fundo de seções de destaque e cartões              |
| Terracota         | `#c8763a` | Cor secundária — badges, alertas e ODS             |
| Terracota suave   | `#fdf0e6` | Fundo de avisos e blocos de atenção                |
| Off-white         | `#f9f7f4` | Fundo geral da página                              |
| Cinza médio       | `#555555` | Texto secundário e rótulos de formulário           |
| Borda suave       | `#ddd5cc` | Bordas de cartões e separadores                    |

### Justificativa

O **verde musgo** (`#3d7a4f`) foi escolhido como cor principal por sua associação cultural imediata com natureza, saúde e frescor — elementos coerentes com uma ferramenta de orientação alimentar. É uma tonalidade com saturação controlada, o que evita o cansaço visual em sessões mais longas de uso.

O **terracota** (`#c8763a`) entra como cor de apoio para criar contraste quente: enquanto o verde remete ao vegetal e ao saudável, o terracota evoca o grão, a terra e o alimento natural. Juntos, formam uma identidade visual que foge do estereótipo clínico do branco-azul e aproxima o projeto de um tom mais acolhedor.

O fundo **off-white** (`#f9f7f4`) substitui o branco puro para reduzir a fadiga visual em telas, mantendo luminosidade sem o excesso de brilho.

Do ponto de vista de **legibilidade e contraste**, a combinação de texto escuro (`#1e1e1e`) sobre fundo claro (`#f9f7f4`, `#e8f5ec` ou `#ffffff`) garante razões de contraste acima de 7:1, em conformidade com o nível AAA das diretrizes WCAG. O verde escuro sobre branco também supera a razão mínima AA (4,5:1) em todos os contextos de uso.

## 🚀 Tecnologias Utilizadas
- **HTML5:** Estruturação semântica das páginas.
- **CSS3:** Estilização, layout em Flexbox/Grid e responsividade.
- **JavaScript:** Lógica de cálculo matemático, manipulação do DOM e interatividade.

## 📂 Estrutura do Projeto
```
palatato/
├── assets/
│   ├── css/
│   │   └── style.css         # Estilos globais e de componentes
│   ├── js/
│   │   └── script.js         # Lógica de cálculo e manipulação de tela
│   └── img/                  # Logotipos, ícones e imagens dos pratos
├── index.html                # Página inicial com a calculadora
├── resultados.html           # Tela de exibição dos cálculos e dietas
└── sobre.html                # Informações sobre o projeto e a ODS 3
```

## 🛠️ Como executar
1. Faça o clone deste repositório:
   `git clone https://github.com/otaviogrotto/palatato.git`
2. Acesse a pasta do projeto.
3. Abra o arquivo `index.html` em qualquer navegador web de sua preferência.
*(Nenhuma instalação de dependências ou servidor local é estritamente necessária para rodar a aplicação base).*

## ⚠️ Aviso Legal
Esta é uma ferramenta acadêmica de triagem e conscientização. Os resultados gerados **não substituem** a consulta com um profissional de Nutrição habilitado. 

## 👨‍💻 Autor
Desenvolvido por **Otávio Augusto Grotto Silva** para a disciplina de Introdução ao Desenvolvimento Web - UFFS Campus Chapecó/SC.
