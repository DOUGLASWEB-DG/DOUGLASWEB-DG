<!DOCTYPE html>
<html lang="pt-BR" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Douglas Júlio | Desenvolvedor Full Stack</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: '#8b5cf6',
            surface: '#0d1117',
            card: '#161b22'
          }
        }
      }
    }
  </script>
</head>
<body class="bg-surface text-gray-200 font-sans antialiased min-h-screen flex flex-col justify-between">

  <header class="max-w-5xl mx-auto w-full p-6 flex justify-between items-center border-b border-gray-800">
    <span class="text-xl font-bold tracking-tight text-brand">Douglas.dev</span>
    <div class="flex items-center gap-3">
      <img src="https://komarev.com/ghpvc/?username=DOUGLASWEB-DGme&style=flat-square&color=blueviolet" alt="Contador de visualizações" />
    </div>
  </header>

  <main class="max-w-5xl mx-auto w-full p-6 space-y-12 my-auto">
    <section class="text-center space-y-4 py-8">
      <div class="inline-flex items-center gap-2 bg-brand/10 text-brand px-4 py-1.5 rounded-full text-sm font-medium border border-brand/20">
        <span>Olá!</span>
        <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="20" alt="Wave" />
      </div>
      <h1 class="text-4xl md:text-6xl font-extrabold text-white tracking-tight">
        Meu nome é <span class="text-transparent bg-clip-text bg-gradient-to-r from-violet-400 to-purple-600">Douglas Júlio</span>
      </h1>
      <h2 class="text-xl md:text-2xl text-gray-400 font-medium">Desenvolvedor Full Stack & Entusiasta de IoT</h2>
      <p class="max-w-2xl mx-auto text-gray-400 leading-relaxed">
        Interessado em tecnologia, do software ao hardware — construo desde ecossistemas web de alta performance até automações e embarcados.
      </p>
    </section>

    <section class="grid md:grid-cols-2 gap-6">
      <div class="bg-card p-6 rounded-xl border border-gray-800 space-y-3">
        <h3 class="text-lg font-semibold text-white flex items-center gap-2">
          <span>🎓</span> Formação e Atuação em TI
        </h3>
        <p class="text-sm text-gray-400 leading-relaxed">
          Estudante de Análise e Desenvolvimento de Sistemas (ADS). Atuo como Analista de Suporte em TI gerenciando ativos, chamados de infraestrutura (GLPI) e rotinas operacionais técnicas.
        </p>
      </div>

      <div class="bg-card p-6 rounded-xl border border-gray-800 space-y-3">
        <h3 class="text-lg font-semibold text-white flex items-center gap-2">
          <span>⚙️</span> Ambiente & Produtividade
        </h3>
        <p class="text-sm text-gray-400 leading-relaxed">
          Utilização contínua de distribuições Linux como sistema operacional principal de desenvolvimento e Obsidian para gestão ativa do conhecimento.
        </p>
      </div>
    </section>

    <section class="bg-card p-8 rounded-xl border border-gray-800 text-center space-y-6">
      <div class="space-y-2">
        <span class="text-xs uppercase tracking-widest text-brand font-semibold">Projeto Principal</span>
        <h3 class="text-2xl font-bold text-white">🚀 navalha.app</h3>
        <p class="text-gray-400 text-sm max-w-xl mx-auto">SaaS de Gestão para Barbearias focado em alta performance e produtividade.</p>
      </div>

      <div class="flex flex-wrap justify-center gap-3">
        <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
        <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
        <img src="https://img.shields.io/badge/-Evolution_API-00E676?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Evolution API" />
      </div>
    </section>

    <section class="space-y-6 text-center">
      <h3 class="text-xl font-bold text-white">Tecnologias & Ferramentas</h3>
      <div class="flex flex-col items-center gap-4">
        <img src="https://skillicons.dev/icons?perline=8&i=nextjs,react,ts,js,nodejs,tailwind,postgres,mysql" alt="Stack Web 1" />
        <img src="https://skillicons.dev/icons?perline=8&i=prisma,docker,html,css,git,github,vscode,figma" alt="Stack Web 2" />
        <div class="flex flex-wrap justify-center gap-2 pt-2">
          <img src="https://skillicons.dev/icons?perline=1&i=arduino" alt="Arduino" />
          <img src="https://img.shields.io/badge/-ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
          <img src="https://img.shields.io/badge/-PlatformIO-FF7F00?style=for-the-badge&logo=platformio&logoColor=white" alt="PlatformIO" />
        </div>
      </div>
    </section>

    <section class="text-center space-y-4 pt-4">
      <h3 class="text-lg font-semibold text-white">Conecte-se comigo</h3>
      <div class="flex justify-center gap-4">
        <a href="https://www.linkedin.com/in/douglas-júlio-da-paz-gusmão-705b0429b" target="_blank" class="hover:opacity-80 transition-opacity">
          <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
        </a>
        <a href="https://www.instagram.com/douglasjulio_02" target="_blank" class="hover:opacity-80 transition-opacity">
          <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
        </a>
      </div>
    </section>
  </main>

  <footer class="border-t border-gray-800 text-center py-6 text-xs text-gray-500">
    <p>© 2026 Douglas Júlio. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
