<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdulrehman's Personal Website</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter Font from Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
    </style>
    <!-- Lucide Icons CDN -->
    <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#hero" class="text-xl font-bold text-gray-900">Abdulrehman.dev</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="text-gray-600 hover:text-blue-600 transition-colors">About</a>
                <a href="#skills" class="text-gray-600 hover:text-blue-600 transition-colors">Skills</a>
                <a href="#projects" class="text-gray-600 hover:text-blue-600 transition-colors">Projects</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600 transition-colors">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-btn" class="md:hidden text-gray-600 hover:text-blue-600 focus:outline-none">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu"><line x1="4" x2="20" y1="12" y2="12"/><line x1="4" x2="20" y1="6" y2="6"/><line x1="4" x2="20" y1="18" y2="18"/></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="md:hidden bg-white shadow-lg hidden">
            <a href="#about" class="block py-2 px-4 text-center text-gray-600 hover:bg-gray-50 transition-colors">About</a>
            <a href="#skills" class="block py-2 px-4 text-center text-gray-600 hover:bg-gray-50 transition-colors">Skills</a>
            <a href="#projects" class="block py-2 px-4 text-center text-gray-600 hover:bg-gray-50 transition-colors">Projects</a>
            <a href="#contact" class="block py-2 px-4 text-center text-gray-600 hover:bg-gray-50 transition-colors">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-4 sm:px-6 lg:px-8 py-12">

        <!-- Hero Section -->
        <section id="hero" class="text-center py-20 md:py-32">
            <div class="flex flex-col items-center">
                <!-- Placeholder for profile image -->
                <img src="https://placehold.co/150x150/e5e7eb/4b5563?text=AR" alt="Abdulrehman's Profile" class="rounded-full shadow-lg mb-6 w-32 h-32 md:w-40 md:h-40 object-cover border-4 border-white">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight mb-2">
                    Hi, I'm <span class="text-blue-600">Abdulrehman</span>
                </h1>
                <p class="text-xl sm:text-2xl text-gray-600 max-w-2xl">
                    A passionate software developer specializing in building modern web applications.
                </p>
                <div class="mt-8 flex justify-center space-x-4">
                    <a href="#projects" class="bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg shadow-md hover:bg-blue-700 transition-colors">View My Work</a>
                    <a href="#contact" class="bg-white text-gray-800 font-semibold py-3 px-6 rounded-lg shadow-md border border-gray-300 hover:bg-gray-50 transition-colors">Get In Touch</a>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-16">
            <div class="bg-white rounded-lg shadow-md p-8 sm:p-12 lg:p-16">
                <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 text-center mb-8">About Me</h2>
                <div class="prose max-w-none text-gray-600 text-lg leading-relaxed space-y-4">
                    <p>
                        I'm a dedicated and enthusiastic software developer with a strong foundation in front-end and back-end technologies. My journey in tech began with a curiosity for how things work, and it quickly grew into a passion for building intuitive and efficient digital solutions. I enjoy tackling complex problems and turning ideas into reality through clean, well-structured code.
                    </p>
                    <p>
                        I have experience working with modern frameworks and libraries such as React, Node.js, and Python. I'm always eager to learn new technologies and improve my skills. When I'm not coding, you can find me exploring new coffee shops, reading about the latest tech trends, or working on personal projects.
                    </p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-16">
            <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 text-center mb-10">My Skills</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Skill Card Example -->
                <div class="flex flex-col items-center p-6 bg-white rounded-lg shadow-md">
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code-2 text-blue-500 mb-3"><path d="m5 12 7-7 7 7"/><path d="m12 19 7-7-7-7"/></svg>
                    <h3 class="text-lg font-semibold text-gray-800">Web Development</h3>
                    <p class="text-sm text-gray-500 text-center mt-2">HTML, CSS, JavaScript</p>
                </div>
                <!-- Skill Card Example -->
                <div class="flex flex-col items-center p-6 bg-white rounded-lg shadow-md">
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-layout-grid text-blue-500 mb-3"><rect width="18" height="18" x="3" y="3" rx="2" ry="2"/><line x1="3" x2="21" y1="9" y2="9"/><line x1="3" x2="21" y1="15" y2="15"/><line x1="9" x2="9" y1="3" y2="21"/><line x1="15" x2="15" y1="3" y2="21"/></svg>
                    <h3 class="text-lg font-semibold text-gray-800">Frameworks</h3>
                    <p class="text-sm text-gray-500 text-center mt-2">React, Vue, Angular</p>
                </div>
                <!-- Skill Card Example -->
                <div class="flex flex-col items-center p-6 bg-white rounded-lg shadow-md">
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-server text-blue-500 mb-3"><rect width="20" height="8" x="2" y="2" rx="2" ry="2"/><rect width="20" height="8" x="2" y="14" rx="2" ry="2"/><line x1="6" x2="6" y1="6" y2="6"/><line x1="6" x2="6" y1="18" y2="18"/></svg>
                    <h3 class="text-lg font-semibold text-gray-800">Backend</h3>
                    <p class="text-sm text-gray-500 text-center mt-2">Node.js, Python</p>
                </div>
                <!-- Skill Card Example -->
                <div class="flex flex-col items-center p-6 bg-white rounded-lg shadow-md">
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-database text-blue-500 mb-3"><ellipse cx="12" cy="5" rx="9" ry="3"/><path d="M3 5V19A9 3 0 0 0 21 19V5"/><path d="M21 12c0 1.66-4 3-9 3s-9-1.34-9-3"/></svg>
                    <h3 class="text-lg font-semibold text-gray-800">Database</h3>
                    <p class="text-sm text-gray-500 text-center mt-2">SQL, MongoDB</p>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-16">
            <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 text-center mb-10">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Project Card Example -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/600x400/e0f2fe/1e40af?text=Project+1" alt="Project 1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Project Name 1</h3>
                        <p class="text-gray-600 mb-4">A brief description of the project. Mention the technologies used and its purpose.</p>
                        <a href="#" class="inline-flex items-center text-blue-600 font-semibold hover:underline">
                            View Project
                            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right ml-1"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                        </a>
                    </div>
                </div>
                <!-- Project Card Example -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/600x400/e0f2fe/1e40af?text=Project+2" alt="Project 2" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Project Name 2</h3>
                        <p class="text-gray-600 mb-4">A brief description of the project. Mention the technologies used and its purpose.</p>
                        <a href="#" class="inline-flex items-center text-blue-600 font-semibold hover:underline">
                            View Project
                            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right ml-1"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16">
            <div class="bg-white rounded-lg shadow-md p-8 sm:p-12 lg:p-16 text-center">
                <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 mb-4">Get In Touch</h2>
                <p class="text-lg text-gray-600 mb-8 max-w-xl mx-auto">
                    I'm always open to new opportunities and collaborations. Feel free to reach out!
                </p>
                <a href="mailto:abdulrehman@example.com" class="bg-blue-600 text-white font-semibold py-3 px-8 rounded-lg shadow-md hover:bg-blue-700 transition-colors inline-flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-mail mr-2"><rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
                    Email Me
                </a>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-6">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm">
            <p>&copy; 2024 Abdulrehman. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Toggle mobile menu visibility
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Hide mobile menu when a link is clicked
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Initialize Lucide icons
        lucide.createIcons();
    </script>

</body>
</html>
