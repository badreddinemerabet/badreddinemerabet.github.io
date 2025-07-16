<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Badreddine Merabet | Electrical Engineering Researcher</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .nav-link {
            position: relative;
        }
        .nav-link:after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        .nav-link:hover:after {
            width: 100%;
        }
        .active:after {
            width: 100%;
        }
        .timeline-item:not(:last-child):after {
            content: '';
            position: absolute;
            left: 7px;
            top: 24px;
            height: 100%;
            width: 2px;
            background: #e5e7eb;
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800 bg-gray-50">
    <!-- Header/Navigation -->
    <header class="fixed w-full bg-white shadow-sm z-50">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="text-2xl font-bold text-blue-600">Dr. Badreddine Merabet</div>
                <nav class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-blue-600">Home</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-blue-600">About</a>
                    <a href="#research" class="nav-link text-gray-700 hover:text-blue-600">Research</a>
                    <a href="#publications" class="nav-link text-gray-700 hover:text-blue-600">Publications</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600">Contact</a>
                </nav>
                <button id="mobile-menu-button" class="md:hidden text-gray-600 focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white py-2 px-4 shadow-lg">
            <a href="#home" class="block py-2 text-gray-700 hover:text-blue-600">Home</a>
            <a href="#about" class="block py-2 text-gray-700 hover:text-blue-600">About</a>
            <a href="#research" class="block py-2 text-gray-700 hover:text-blue-600">Research</a>
            <a href="#publications" class="block py-2 text-gray-700 hover:text-blue-600">Publications</a>
            <a href="#contact" class="block py-2 text-gray-700 hover:text-blue-600">Contact</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg text-white pt-32 pb-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Dr. Badreddine Merabet</h1>
                <h2 class="text-2xl md:text-3xl font-semibold mb-6">Electrical Engineering Researcher</h2>
                <p class="text-lg mb-8 text-blue-100">PhD in Electrical Engineering from Hefei University of Technology. Specializing in control systems, automation, and renewable energy integration.</p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-lg font-medium hover:bg-blue-50 transition duration-300">Contact Me</a>
                    <a href="#research" class="border-2 border-white text-white px-6 py-3 rounded-lg font-medium hover:bg-white hover:text-blue-600 transition duration-300">My Research</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-4 border-white shadow-xl">
                    <!-- Placeholder for profile image -->
                    <div class="w-full h-full bg-gray-300 flex items-center justify-center">
                        <i class="fas fa-user text-6xl text-gray-500"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">About Me</h2>
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <h3 class="text-2xl font-semibold mb-4 text-blue-600">Biography</h3>
                    <p class="text-gray-700 mb-6 leading-relaxed">
                        Dr. Badreddine Merabet is an accomplished researcher in the field of Electrical Engineering, with a PhD from Hefei University of Technology, China. His research focuses on control systems, automation, and the integration of renewable energy sources into power grids.
                    </p>
                    <p class="text-gray-700 mb-6 leading-relaxed">
                        With extensive experience in both academia and industry, Dr. Merabet has contributed to numerous research projects and published several papers in prestigious journals. His work bridges theoretical advancements with practical applications in energy systems.
                    </p>
                    <div class="flex flex-wrap gap-4 mt-8">
                        <div class="bg-blue-50 px-4 py-2 rounded-lg flex items-center">
                            <i class="fas fa-graduation-cap text-blue-600 mr-2"></i>
                            <span>PhD in Electrical Engineering</span>
                        </div>
                        <div class="bg-blue-50 px-4 py-2 rounded-lg flex items-center">
                            <i class="fas fa-university text-blue-600 mr-2"></i>
                            <span>Hefei University of Technology</span>
                        </div>
                        <div class="bg-blue-50 px-4 py-2 rounded-lg flex items-center">
                            <i class="fas fa-flask text-blue-600 mr-2"></i>
                            <span>10+ Years Research Experience</span>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-semibold mb-6 text-blue-600">Education & Experience</h3>
                    <div class="space-y-8 relative">
                        <!-- Timeline Item 1 -->
                        <div class="timeline-item relative pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-blue-600 border-4 border-blue-100"></div>
                            <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                                <h4 class="font-bold text-lg mb-1">PhD in Electrical Engineering</h4>
                                <p class="text-gray-600 mb-2">Hefei University of Technology, China</p>
                                <p class="text-gray-500 text-sm">2015 - 2019</p>
                                <p class="mt-2 text-gray-700">Focused on advanced control systems for renewable energy integration.</p>
                            </div>
                        </div>
                        
                        <!-- Timeline Item 2 -->
                        <div class="timeline-item relative pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-blue-600 border-4 border-blue-100"></div>
                            <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                                <h4 class="font-bold text-lg mb-1">Research Associate</h4>
                                <p class="text-gray-600 mb-2">Hefei University of Technology</p>
                                <p class="text-gray-500 text-sm">2019 - Present</p>
                                <p class="mt-2 text-gray-700">Conducting research in smart grid technologies and control algorithms.</p>
                            </div>
                        </div>
                        
                        <!-- Timeline Item 3 -->
                        <div class="timeline-item relative pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-blue-600 border-4 border-blue-100"></div>
                            <div class="bg-gray-50 p-6 rounded-lg shadow-sm">
                                <h4 class="font-bold text-lg mb-1">MSc in Electrical Engineering</h4>
                                <p class="text-gray-600 mb-2">University of Science and Technology</p>
                                <p class="text-gray-500 text-sm">2012 - 2014</p>
                                <p class="mt-2 text-gray-700">Specialized in power systems and control engineering.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Research Section -->
    <section id="research" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">Research Interests</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">My research spans several key areas in electrical engineering and automation systems</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Research Card 1 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-bolt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Power System Control</h3>
                    <p class="text-gray-700">Developing advanced control algorithms for stable and efficient power system operation, particularly in systems with high renewable energy penetration.</p>
                </div>
                
                <!-- Research Card 2 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-solar-panel text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Renewable Energy Integration</h3>
                    <p class="text-gray-700">Research on innovative methods to integrate solar, wind, and other renewable sources into existing power grids while maintaining stability.</p>
                </div>
                
                <!-- Research Card 3 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-robot text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Industrial Automation</h3>
                    <p class="text-gray-700">Design and implementation of intelligent control systems for industrial automation applications.</p>
                </div>
                
                <!-- Research Card 4 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-brain text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">AI in Power Systems</h3>
                    <p class="text-gray-700">Application of machine learning and artificial intelligence techniques for power system optimization and fault detection.</p>
                </div>
                
                <!-- Research Card 5 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-microchip text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Smart Grid Technologies</h3>
                    <p class="text-gray-700">Research on next-generation smart grid technologies including distributed control and demand response systems.</p>
                </div>
                
                <!-- Research Card 6 -->
                <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-charging-station text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Energy Storage Systems</h3>
                    <p class="text-gray-700">Development of control strategies for battery and other energy storage systems in grid applications.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects/Publications Section -->
    <section id="publications" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">Selected Publications</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">A selection of my most significant research publications</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Publication 1 -->
                <div class="project-card bg-gray-50 p-6 rounded-lg transition duration-300 hover:shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 text-blue-600 p-3 rounded-full mr-4">
                            <i class="fas fa-book-open"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-lg">Advanced Control Strategies for Microgrids</h3>
                            <p class="text-sm text-gray-600">IEEE Transactions on Power Systems, 2021</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">This paper presents novel control strategies for islanded microgrids with high renewable penetration, demonstrating improved stability and power quality.</p>
                    <a href="#" class="text-blue-600 hover:underline flex items-center">
                        <span>View Publication</span>
                        <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
                
                <!-- Publication 2 -->
                <div class="project-card bg-gray-50 p-6 rounded-lg transition duration-300 hover:shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 text-blue-600 p-3 rounded-full mr-4">
                            <i class="fas fa-book-open"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-lg">AI-Based Fault Detection in Power Systems</h3>
                            <p class="text-sm text-gray-600">Energy Conversion and Management, 2020</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">A machine learning approach for real-time fault detection and classification in power transmission systems, achieving 98.7% accuracy.</p>
                    <a href="#" class="text-blue-600 hover:underline flex items-center">
                        <span>View Publication</span>
                        <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
                
                <!-- Publication 3 -->
                <div class="project-card bg-gray-50 p-6 rounded-lg transition duration-300 hover:shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 text-blue-600 p-3 rounded-full mr-4">
                            <i class="fas fa-book-open"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-lg">Distributed Control of Renewable Energy Sources</h3>
                            <p class="text-sm text-gray-600">Renewable Energy, 2019</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">This research proposes a distributed control framework for coordinating multiple renewable energy sources in a microgrid environment.</p>
                    <a href="#" class="text-blue-600 hover:underline flex items-center">
                        <span>View Publication</span>
                        <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
                
                <!-- Publication 4 -->
                <div class="project-card bg-gray-50 p-6 rounded-lg transition duration-300 hover:shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 text-blue-600 p-3 rounded-full mr-4">
                            <i class="fas fa-book-open"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-lg">Energy Storage Optimization for Grid Applications</h3>
                            <p class="text-sm text-gray-600">Journal of Energy Storage, 2018</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">An optimization framework for sizing and operating battery energy storage systems in grid applications with renewable energy sources.</p>
                    <a href="#" class="text-blue-600 hover:underline flex items-center">
                        <span>View Publication</span>
                        <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-block bg-blue-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                    View All Publications
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">Get In Touch</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">I'm always interested in discussing research collaborations or answering questions about my work.</p>
            
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <div class="bg-white p-8 rounded-xl shadow-sm">
                        <h3 class="text-xl font-bold mb-6 text-blue-600">Contact Information</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="text-blue-600 mt-1 mr-4">
                                    <i class="fas fa-envelope"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium text-gray-800">Email</h4>
                                    <p class="text-gray-600">b.merabet@hfut.edu.cn</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="text-blue-600 mt-1 mr-4">
                                    <i class="fas fa-university"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium text-gray-800">Institution</h4>
                                    <p class="text-gray-600">Hefei University of Technology</p>
                                    <p class="text-gray-600">School of Electrical Engineering and Automation</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="text-blue-600 mt-1 mr-4">
                                    <i class="fas fa-map-marker-alt"></i>
                                </div>
                                <div>
                                    <h4 class="font-medium text-gray-800">Address</h4>
                                    <p class="text-gray-600">193 Tunxi Road, Hefei, Anhui, China</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="font-medium text-gray-800 mb-4">Connect With Me</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center hover:bg-blue-600 hover:text-white transition duration-300">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center hover:bg-blue-600 hover:text-white transition duration-300">
                                    <i class="fab fa-researchgate"></i>
                                </a>
                                <a href="#" class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center hover:bg-blue-600 hover:text-white transition duration-300">
                                    <i class="fab fa-google-scholar"></i>
                                </a>
                                <a href="#" class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center hover:bg-blue-600 hover:text-white transition duration-300">
                                    <i class="fas fa-graduation-cap"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2">
                    <div class="bg-white p-8 rounded-xl shadow-sm">
                        <h3 class="text-xl font-bold mb-6 text-blue-600">Send Me a Message</h3>
                        <form>
                            <div class="mb-6">
                                <label for="name" class="block text-gray-700 mb-2">Name</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            
                            <div class="mb-6">
                                <label for="email" class="block text-gray-700 mb-2">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            
                            <div class="mb-6">
                                <label for="subject" class="block text-gray-700 mb-2">Subject</label>
                                <input type="text" id="subject" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 mb-2">Message</label>
                                <textarea id="message" rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <h3 class="text-2xl font-bold">Dr. Badreddine Merabet</h3>
                    <p class="text-gray-400 mt-2">Electrical Engineering Researcher</p>
                </div>
                
                <div class="flex flex-col items-center md:items-end">
                    <div class="flex space-x-6 mb-4">
                        <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                            <i class="fab fa-linkedin-in text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                            <i class="fab fa-researchgate text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                            <i class="fab fa-google-scholar text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition duration-300">
                            <i class="fas fa-graduation-cap text-xl"></i>
                        </a>
                    </div>
                    <p class="text-gray-400 text-sm">© 2023 Dr. Badreddine Merabet. All rights reserved.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="back-to-top" class="fixed bottom-8 right-8 w-12 h-12 bg-blue-600 text-white rounded-full shadow-lg hidden items-center justify-center">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                document.getElementById('mobile-menu').classList.add('hidden');
                
                // Update active nav link
                document.querySelectorAll('.nav-link').forEach(link => {
                    link.classList.remove('active');
                });
                this.classList.add('active');
            });
        });

        // Back to top button
        const backToTopButton = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', function() {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
                backToTopButton.classList.add('flex');
            } else {
                backToTopButton.classList.add('hidden');
                backToTopButton.classList.remove('flex');
            }
        });
        
        backToTopButton.addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Highlight active navigation link based on scroll position
        window.addEventListener('scroll', function() {
            const sections = document.querySelectorAll('section');
            let currentSection = '';
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 100;
                if (window.pageYOffset >= sectionTop) {
                    currentSection = section.getAttribute('id');
                }
            });
            
            document.querySelectorAll('.nav-link').forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href') === `#${currentSection}`) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>
