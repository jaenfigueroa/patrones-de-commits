<h1 align="center">
📄<br>Patrones para commits
</h1>

<h1 align="center">
  <img src="gitcommit.png">
</h1>

Según la documentación de **Conventional Commits**, los Commits Semánticos son una convención simple para utilizar en los mensajes de commit. Esta convención establece reglas para crear un historial de commits explícito, lo que facilita la creación de herramientas automatizadas.

Estos commits ayudarán a ti y a tu equipo a comprender de manera más fácil qué cambios se realizaron en el código que se ha commitado.

Esta identificación se realiza mediante una palabra y un emoji que indica si ese commit se trata de un cambio de código, actualización de paquetes, documentación, cambio visual, pruebas, etc.

## 📚 Ebook

> Este repositorio es un proyecto gratuito para la comunidad de desarrolladores. Sin embargo, puedo ayudarte comprando el ebook "eFront" si estás interesado en aprender o mejorar tus habilidades de desarrollo frontend. El ebook es completo y cubre tecnologías muy demandadas en el mercado como HTML, CSS, JavaScript, Sass, Bootstrap, React, React Router, TypeScript, styled-components, Tailwind CSS, React Hook Form, Radix UI, Storybook, Cypress, Next.js, y mucho más. Tiene un valor de R$25,00 y tu compra me ayuda a producir y proporcionar más contenido gratuito para la comunidad. Adquiérelo ahora y comienza tu viaje en el desarrollo frontend..

- eFront - Estudando frontend do zero. [Haz clic aquí para comprar](https://iuricode.com/efront)

## 🦄 Tipo y Descripción.

El commit semántico tiene los siguientes elementos estructurales (tipos) que informan la intención de tu commit al usuario de tu código.

- `feat`-Los commits del tipo "feat" indican que se está incluyendo una **nueva característica** en el código (relacionado con la versión MINOR del versionado semántico).

- `fix` - Los commits del tipo "fix" indican que el fragmento de código commitado está **solucionando un problema** (corrección de errores) (relacionado con el PATCH del versionamiento semántico).

- `docs` - Los commits del tipo "docs" indican que ha habido **cambios en la documentación**, como por ejemplo en el archivo README de tu repositorio. Esto no incluye cambios en el código.

- `test` - Los commits del tipo "test" se utilizan cuando se realizan **cambios en pruebas**, ya sea creando, modificando o eliminando pruebas unitarias. Esto no incluye cambios en el código.

- `build` - Los commits del tipo "build" se utilizan cuando se realizan modificaciones en **archivos de construcción (build) y dependencias**.

- `perf` - Los commits del tipo "perf" se utilizan para identificar cualquier cambio de código relacionado con **rendimiento**.

- `style` - Los commits del tipo "style" indican que ha habido cambios relacionados con **formatos de código**, como puntos y comas, espacios al final de las líneas, reglas de lint, etc. Esto no incluye cambios en el código en sí.

- `refactor` - Los commits del tipo "refactor" se refieren a cambios debido a **refactorizaciones que no alteran la funcionalidad**, como por ejemplo, cambios en el formato en el que se procesa una parte de la interfaz, pero manteniendo la misma funcionalidad, o mejoras de rendimiento realizadas después de una revisión de código.

- `chore` - Los commits del tipo "chore" indican **actualizaciones de tareas** de construcción, configuraciones administrativas, paquetes, etc. Por ejemplo, agregar un paquete al archivo gitignore. Esto no incluye cambios en el código en sí.

- `ci` - Los commits del tipo "ci" indican cambios relacionados con **integración continua** (_continuous integration_). Estos cambios pueden estar relacionados con configuraciones, scripts o procesos de integración continua utilizados en el proyecto.

## ☑️ Recomendações

- Adicione um título consistente com o título do conteúdo;
- Recomendamos que na primeira linha deve ter no máximo 4 palavras;
- Para descrever com detalhes, usar a descrição do commit;
- Usar um emoji no início da mensagem de commit representando sobre o commit;
- Um link precisa ser adicionado em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados;

## 🍧 Complementos de Commits

- **Rodapé:** Geralmente uma informação sobre o revisor e numero de card de trello ou jira 
  Exemplo: Reviewed-by: Elisandro Mello Refs #133
- **Corpo** : descrições mais precisas do que está contido no commit, apresentando impactos e os motivos pelos quais foram empregadas as alterações no código, como também instruções essenciais para intervenções futuras. 
  Exemplo: see the issue for details on typos fixed.
- **Descrições**:  uma descrição sucinta da mudança
  Exemplo: correct minor typos in code

## 💈 Padrões de emojis

<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit inicial"</code>
      </td>
      <td>🎉 Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Atualizaçao do README"</code>
      </td>
      <td>📚 docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito na linha 50"</code>
      </td>
      <td>🐛 fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Pagina de login"</code>
      </td>
      <td>✨ feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificaçao no Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💄 feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Criando novo teste"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

<div align="center">
  <br/>
    <div>
      <h1>Open Source</h1>
      <sub>Copyright © 2023 - <a href="https://github.com/iuricode">iuricode</sub></a>
    </div>
    <br/>
    <p> 
      <a href="https://github.com/iuricode/padroes-de-commits/blob/main/LICENSE.md">LICENÇA</a>
    </p>
    💖
</div>
