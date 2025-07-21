<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Roach Media Co.</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/dist/tailwind.min.css" rel="stylesheet">
    <style>
      :root {
        --cyan-dark: #0e7c86;
      }
    </style>
  </head>
  <body class="bg-white text-black dark:bg-black dark:text-white transition-colors duration-300">
    <!-- Navbar -->
    <header class="flex justify-between items-center px-6 py-4 border-b border-gray-200 dark:border-gray-800">
      <h1 class="text-2xl font-bold">Roach Media Co.</h1>
      <nav class="space-x-6">
        <a href="#home" class="hover:text-[var(--cyan-dark)]">Home</a>
        <a href="#portfolio" class="hover:text-[var(--cyan-dark)]">Portfolio</a>
      </nav>
    </header>

    <!-- Hero -->
    <section id="home" class="h-[80vh] flex flex-col justify-center items-center text-center bg-gradient-to-b from-white to-gray-100 dark:from-black dark:to-gray-900">
      <h2 class="text-4xl md:text-6xl font-bold mb-4">Capturing Stories</h2>
      <p class="text-lg md:text-xl text-gray-600 dark:text-gray-400 max-w-xl">Roach Media Co. is your lens for cinematic visuals and striking photography.</p>
    </section>

    <!-- Portfolio -->
    <section id="portfolio" class="px-6 py-12 bg-gray-50 dark:bg-gray-950">
      <h3 class="text-3xl font-semibold mb-8 text-center">Portfolio</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <!-- Sample Images -->
        <div class="aspect-video bg-gray-200 dark:bg-gray-800 rounded-xl overflow-hidden shadow-lg">
          <img src="/images/photo1.jpg" alt="Photography Sample 1" class="object-cover w-full h-full" />
        </div>
        <div class="aspect-video bg-gray-200 dark:bg-gray-800 rounded-xl overflow-hidden shadow-lg">
          <video controls class="w-full h-full">
            <source src="/videos/video1.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <!-- More images/videos as needed -->
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 text-center text-sm text-gray-500 dark:text-gray-400">
      &copy; 2025 Roach Media Co. | All rights reserved
    </footer>
  </body>
</html>
