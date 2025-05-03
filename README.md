
<body>

  <h1>🎲 Sorteador de Números</h1>
  <p>Um projeto simples de sorteador de números desenvolvido com <strong>JavaScript</strong> e <strong>CSS</strong>, utilizando <strong>Grunt</strong> para automação de tarefas, incluindo compilação de <strong>LESS</strong> e <strong>SASS</strong>.</p>

  <h2>📌 Tecnologias Utilizadas</h2>
  <ul>
    <li><strong>JavaScript</strong> – lógica do sorteador</li>
    <li><strong>CSS</strong> – estilização final</li>
    <li><strong>LESS</strong> – pré-processador CSS</li>
    <li><strong>SASS</strong> – pré-processador CSS</li>
    <li><strong>Grunt</strong> – automação de tarefas</li>
  </ul>

  <h2>⚙️ Funcionalidades</h2>
  <ul>
    <li>Sorteio de números aleatórios dentro de um intervalo definido</li>
    <li>Estilização responsiva com LESS e SASS</li>
    <li>Compilação automática de arquivos <code>.less</code> e <code>.scss</code> via Grunt</li>
    <li>Interface simples e intuitiva</li>
  </ul>

  <h2>🚀 Como Executar</h2>
  <ol>
    <li>Clone o repositório:
      <pre><code>git clone https://github.com/paamelaamaro/sorteador_grunt.git
cd sorteador_grunt</code></pre>
    </li>
    <li>Instale as dependências (com Node.js e Grunt CLI instalados):
      <pre><code>npm install</code></pre>
    </li>
    <li>Rode o Grunt para compilar os estilos:
      <pre><code>grunt</code></pre>
    </li>
    <li>Abra o arquivo <code>index.html</code> no navegador.</li>
  </ol>

  <h2>📁 Estrutura do Projeto</h2>
  <pre><code>sorteador_grunt/
├── Gruntfile.js
├── package.json
├── index.html
├── js/
│   └── main.js
├── styles/
│   ├── main.less
│   ├── main.scss
│   └── style.css (gerado)
└── dist/
    └── app.min.js</code></pre>

  <h2>📸 Preview</h2>
  (https://sorteadorgruntpam.vercel.app/)

  <h2>🛠 Tarefas Grunt Configuradas</h2>
  <ul>
    <li><code>less</code>: Compila arquivos LESS para CSS</li>
    <li><code>sass</code>: Compila arquivos SASS para CSS</li>
    <li><code>watch</code>: Observa alterações nos arquivos</li>
    <li><code>uglify</code>: Minifica arquivos JS</li>
  </ul>

  <h2>🧑‍💻 Autor</h2>
  <p>
    Nome: <strong>Paamela Amaro</strong><br />
    GitHub: <a href="https://github.com/paamelaamaro" target="_blank">@paamelaamaro</a>
  </p>

</body>
</html>
