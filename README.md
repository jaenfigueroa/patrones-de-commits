Repositorio original: [iuricode/padroes-de-commits](https://github.com/iuricode/padroes-de-commits)

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

## ☑️ Recomendaciones

- Agregar un título consistente con el título del contenido.
- Se recomienda que la primera línea tenga un máximo de 4 palabras.
- Utilizar la descripción del commit para proporcionar detalles.
- Utilizar un emoji al inicio del mensaje de commit que represente el commit.
- Agregar un enlace en su forma auténtica, sin acortadores de enlaces ni enlaces afiliados.

## 🍧 Complementos de Commits

- **Pie de página**: Generalmente contiene información sobre el revisor y el número de la tarjeta de Trello o Jira.
Ejemplo: Revisado por: Elisandro Mello Refs #133
- **Cuerpo**: Descripciones más precisas de lo que contiene el commit, presentando los impactos y las razones por las que se realizaron los cambios en el código, así como instrucciones importantes para futuras intervenciones.
Ejemplo: ver el problema para obtener detalles sobre los errores corregidos.
- **Descripciones**: Una descripción breve del cambio.
Ejemplo: corregir errores menores en el código.

## 💈 Patrones de emojis

<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
      <th>Palabra Clave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Accesibilidad</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Añadir un test</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Añadir una dependencia</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Cambios en la revisión del código</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animaciones y transiciones</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Corrección de errores</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentarios</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuración</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Despliegue</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentación</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>En proceso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Diseño de la interfaz</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideas (tareas)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renombrar</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Nueva función</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json en JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Rendimiento</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refactorización</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Eliminar un archivo</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Eliminar una dependencia</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividad</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revirtiendo cambios</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Seguridad</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Etiqueta de versión</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Prueba de aprobación</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Pruebas</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipado</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Gestión de errores</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 💻 Ejemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado en GitHub</th>
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
        <code>git commit -m ":books: docs: Actualización de README"</code>
      </td>
      <td>📚 docs: Actualización de README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Bucle infinito en la línea 50"</code>
      </td>
      <td>🐛 fix: Bucle infinito en la línea 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Página de inicio de sesión"</code>
      </td>
      <td>✨ feat: Página de inicio de sesión</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificación en el Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificación en el Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Cambio a funciones de flecha"</code>
      </td>
      <td>♻️ refactor: Cambio a funciones de flecha</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Mejora del tiempo de respuesta"</code>
      </td>
      <td>⚡ perf: Mejora del tiempo de respuesta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revirtiendo cambios ineficientes"</code>
      </td>
      <td>💥 fix: Revirtiendo cambios ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilización CSS del formulario"</code>
      </td>
      <td>💄 feat: Estilización CSS del formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Creando nueva prueba"</code>
      </td>
      <td>🧪 test: Creando nueva prueba</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentarios sobre la función LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentarios sobre la función LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

## Traducciones

También esta disponible en otros idiomas

- ![br](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png) **Portugués brasileño** [iuricode/padroes-de-commits](https://github.com/iuricode/padroes-de-commits)

<div align="center">
  <br/>
    <div>
      <h1>Open Source</h1>
      <sub>Copyright © 2023 - <a href="https://github.com/iuricode">iuricode</sub></a>
    </div>
    <br/>
    <p>
      <a href="https://github.com/iuricode/padroes-de-commits/blob/main/LICENSE.md">LICENCIA</a>
    </p>
    💖
</div>
