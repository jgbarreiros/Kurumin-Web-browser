Projeto Kurumin
📌 Descrição Geral

O Kurumin é um navegador web desenvolvido como Trabalho de Conclusão de Curso (TCC), com foco em simplicidade, usabilidade e integração com tecnologias web. O projeto utiliza Python com PyQt5 para a interface gráfica e Qt WebEngine para renderização de páginas web, além de uma página inicial desenvolvida em HTML e CSS.

O navegador oferece funcionalidades básicas encontradas em browsers modernos, como navegação por abas, botões de controle (voltar, avançar, recarregar, página inicial), barra de endereços e integração com um mecanismo de busca.

🎯 Objetivo do Projeto

O objetivo do Kurumin é demonstrar, de forma prática:

A aplicação de conceitos de programação desktop com Python

O uso de frameworks gráficos (PyQt5)

A integração entre aplicações desktop e tecnologias web

O desenvolvimento de um software funcional como produto final de TCC

🛠️ Tecnologias Utilizadas

Python 3

PyQt5

Qt WebEngine

HTML5

CSS3
📂 Estrutura do Projeto
Kurumin/
│
├── main2.0.py # Código principal do navegador
├── index.html # Página inicial do navegador
├── style.css # Estilos da página inicial
├── logo.png # Logo da página inicial
├── logo00.png # Ícone da aplicação
├── voltar.png # Ícone de navegação (voltar)
├── seguir.png # Ícone de navegação (avançar)
├── recarregar.png # Ícone de recarregar página
├── cabana.png # Ícone de página inicial
└── README.md # Documentação do projeto

⚙️ Funcionalidades

Navegação por abas

Barra de endereços com entrada manual de URLs

Botões de:

Voltar

Avançar

Recarregar

Página inicial

Página inicial personalizada em HTML/CSS

Renderização de páginas web usando Qt WebEngine

🧠 Funcionamento do Código Principal

O arquivo main2.0.py é responsável por:

Criar a janela principal do navegador

Gerenciar abas usando QTabWidget

Controlar a navegação entre páginas

Atualizar a barra de endereços conforme a URL acessada

Definir a página inicial do navegador

A renderização das páginas web é feita através do componente QWebEngineView.

🎓 Considerações Finais

O projeto Kurumin cumpre o papel de demonstrar conhecimentos adquiridos ao longo do curso, unindo programação, lógica, interfaces gráficas e web. Trata-se de um navegador funcional, com arquitetura simples e clara, ideal para fins acadêmicos e didáticos.
