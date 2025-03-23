<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NUEL - Learn Computer Science Online</title>
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config = {
theme: {
extend: {
colors: {
primary: '#4F46E5',
secondary: '#10B981'
},
borderRadius: {
'none': '0px',
'sm': '4px',
DEFAULT: '8px',
'md': '12px',
'lg': '16px',
'xl': '20px',
'2xl': '24px',
'3xl': '32px',
'full': '9999px',
'button': '8px'
}
}
}
}
</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
.course-card:hover { transform: translateY(-4px); }
.testimonial-slider { scroll-behavior: smooth; }
</style>
</head>
<body class="bg-white font-['Inter']">
<nav class="fixed top-0 w-full bg-white/95 backdrop-blur-sm z-50 border-b border-gray-100">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex justify-between h-16">
<div class="flex items-center">
<a href="#" class="text-2xl font-['Pacifico'] text-primary">Computer Science Project</a>
</div>
<div class="hidden md:flex items-center space-x-8">
<a href="#home" class="text-gray-700 hover:text-primary">Home</a>
<a href="#courses" class="text-gray-700 hover:text-primary">Courses</a>
<a href="#resources" class="text-gray-700 hover:text-primary">Resources</a>
<a href="#about" class="text-gray-700 hover:text-primary">About</a>
<a href="#contact" class="text-gray-700 hover:text-primary">Contact</a>
</div>
<div class="flex items-center space-x-4">
<div class="relative">
<input type="text" placeholder="Search courses..." class="w-64 pl-10 pr-4 py-2 text-sm border border-gray-200 rounded-button focus:outline-none focus:border-primary">
<div class="absolute left-3 top-1/2 -translate-y-1/2 w-4 h-4 flex items-center justify-center">
<i class="ri-search-line text-gray-400"></i>
</div>
</div>
<button class="px-4 py-2 text-sm text-gray-700 hover:text-primary !rounded-button">Sign In</button>
<button class="px-4 py-2 text-sm text-white bg-primary hover:bg-primary/90 !rounded-button">Register</button>
</div>
</div>
</a>
</div>
</nav>
<main class="pt-16">
<section class="relative overflow-hidden bg-gradient-to-r from-gray-50 to-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="space-y-8">
<h1 class="text-5xl font-bold text-gray-900 leading-tight">Start Your Coding Journey Today</h1>
<p class="text-xl text-gray-600">Begin your programming adventure with our beginner-friendly courses. Master Python, JavaScript, Data Structures, Algorithms, Web Development and Cloud Computing through hands-on projects and expert guidance.</p>
<div class="flex flex-wrap gap-4 mb-8">
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-2">
<i class="ri-code-s-slash-line text-primary"></i>
</div>
<span class="text-gray-700">Python & JavaScript</span>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-2">
<i class="ri-database-2-line text-primary"></i>
</div>
<span class="text-gray-700">Data Structures</span>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-2">
<i class="ri-braces-line text-primary"></i>
</div>
<span class="text-gray-700">Web Development</span>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-2">
<i class="ri-cloud-line text-primary"></i>
</div>
<span class="text-gray-700">Cloud Computing</span>
</div>
</div>
<button onclick="window.location.href='#courses'" class="px-8 py-4 text-lg text-white bg-primary hover:bg-primary/90 !rounded-button">Start Learning Now</button>
</div>
<div class="relative">
<img src="https://public.readdy.ai/ai/img_res/5f7fcffecffd381ab5ece50bd0f3053f.jpg" class="rounded-lg shadow-2xl" alt="Hero Image">
</div>
</div>
</a>
</div>
</section>
<section id="resources" class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-12">Learning Resources</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-book-open-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Free E-Books</h3>
<p class="text-gray-600 mb-4">Access our collection of programming e-books covering various topics from basics to advanced concepts.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Browse Library →</a>
</div>
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-video-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Video Tutorials</h3>
<p class="text-gray-600 mb-4">Watch step-by-step video tutorials created by our expert instructors to enhance your learning.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Watch Now →</a>
</div>
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-file-paper-2-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Practice Problems</h3>
<p class="text-gray-600 mb-4">Challenge yourself with our curated collection of programming problems and exercises.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Start Practice →</a>
</div>
</div>
</a>
</div>
</section>
<section id="about" class="py-20 bg-gray-50">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="space-y-6">
<h2 class="text-3xl font-bold">About NUEL</h2>
<p class="text-gray-600">NUEL is a leading online platform dedicated to making computer science education accessible to everyone. Founded in 2023, we've helped over 20,000 students and growing. Computer science is an ever-evolving field that's becoming increasingly important for everyone. At NUEL, we make learning programming approachable and engaging for students from all backgrounds.</p>
<div class="space-y-4">
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Industry-relevant curriculum designed by experts</p>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Flexible learning schedule with lifetime access</p>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Dedicated support team available 24/7</p>
</div>
</div>
</a>
</div>
<div class="relative">
<img src="https://static.readdy.ai/image/3b38bec4fae1c2a1ea101ae1e09e7a1e/1fe1bbea2c200e53ff68f24c1de0daa0.png" class="rounded-lg shadow-xl object-cover w-full h-full" alt="About Computer Science Project">
</div>
</div>
</a>
</div>
</section>
<section id="contact" class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<div class="space-y-8">
<h2 class="text-3xl font-bold">Get in Touch</h2>
<p class="text-gray-600">Have questions about our courses or need help getting started? Our team is here to help you begin your learning journey.</p>
<div class="space-y-6">
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-map-pin-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Visit Us</h3>
<p class="text-gray-600">123 Tech Avenue, Silicon Valley, CA 94025</p>
</div>
</div>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-phone-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Call Us</h3>
<p class="text-gray-600">+1 (555) 123-4567</p>
</div>
</div>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-mail-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Email Us</h3>
<p class="text-gray-600">contact@computerscienceproject.com</p>
</div>
</div>
</a>
</div>
</div>
<form class="space-y-6 bg-gray-50 p-8 rounded-lg">
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Full Name</label>
<input type="text" class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary" placeholder="Enter your name">
</div>
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Email Address</label>
<input type="email" class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary" placeholder="Enter your email">
</div>
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Message</label>
<textarea class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary h-32" placeholder="Enter your message"></textarea>
</div>
<button class="w-full px-6 py-3 text-white bg-primary hover:bg-primary/90 !rounded-button">Send Message</button>
</form>
</div>
</div>
</section>
<section class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-12">Start Learning Today</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<a href="#python-javascript" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-code-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Python & JavaScript</h3>
<p class="text-gray-600 mb-4">Master two of the most popular programming languages. Learn Python for backend development and JavaScript for frontend web development. Build real-world projects using both languages.</p>
<div class="flex justify-between items-center">
<span class="text-sm text-primary">48 Lessons</span>
<span class="text-sm text-gray-500">6 Projects</span>
</div>
</div>
</a>

<a href="#data-structures" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-database-2-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Data Structures</h3>
<p class="text-gray-600 mb-4">Deep dive into essential data structures like arrays, linked lists, trees, graphs, and hash tables. Learn implementation and practical applications through hands-on coding exercises.</p>
<div class="flex justify-between items-center">
<span class="text-sm text-primary">36 Lessons</span>
<span class="text-sm text-gray-500">4 Projects</span>
</div>
</div>
</a>

<a href="#web-development" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-code-s-slash-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Web Development</h3>
<p class="text-gray-600 mb-4">Learn modern web development with HTML5, CSS3, JavaScript and popular frameworks. Build responsive websites and interactive web applications from scratch.</p>
<div class="flex justify-between items-center">
<span class="text-sm text-primary">42 Lessons</span>
<span class="text-sm text-gray-500">5 Projects</span>
</div>
</div>
</a>

<a href="#cloud-computing" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-cloud-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Cloud Computing</h3>
<p class="text-gray-600 mb-4">Master cloud platforms like AWS, Azure and GCP. Learn cloud architecture, deployment, scaling and DevOps practices through real-world scenarios.</p>
<div class="flex justify-between items-center">
<span class="text-sm text-primary">32 Lessons</span>
<span class="text-sm text-gray-500">3 Projects</span>
</div>
</div>
</a>
</div>
</div>
</section>
<a href="#data-structures" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-database-2-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Data Structures</h3>
<p class="text-gray-600 mb-4">Understanding simple data structures step by step</p>
<span class="text-sm text-primary">16 Courses</span>
</div>
</a>
<a href="#algorithms" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-flow-chart-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Algorithms</h3>
<p class="text-gray-600 mb-4">Basic problem solving for beginners</p>
<span class="text-sm text-primary">18 Courses</span>
</div>
</a>
<a href="#cloud" class="block">
<div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-cloud-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-2">Cloud Computing</h3>
<p class="text-gray-600 mb-4">Introduction to basic web concepts</p>
<span class="text-sm text-primary">12 Courses</span>
</div>
</a>
</div>
</div>
</section>
<section class="py-20 bg-gray-50">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex justify-between items-center mb-12">
<h2 class="text-3xl font-bold">Featured Courses</h2>
<button onclick="window.location.href='#courses'" class="text-primary hover:text-primary/90 font-semibold">View All Courses</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<a href="#course-details" class="block bg-white rounded-lg shadow-lg overflow-hidden course-card transition-all duration-300">
<img src="https://public.readdy.ai/ai/img_res/f75bd69c7d4fdde9b54c3d040dde1940.jpg" class="w-full h-48 object-cover" alt="Course Image">
<div class="p-6">
<div class="flex items-center justify-between mb-2">
<span class="px-3 py-1 text-xs font-medium text-primary bg-primary/10 rounded-full">Beginner</span>
<span class="text-gray-600">12 weeks</span>
</div>
<h3 class="text-xl font-semibold mb-2">Introduction to Programming</h3>
<p class="text-gray-600 mb-4">Learn the basics of programming with simple examples</p>
<div class="flex items-center justify-between">
<div class="flex items-center">
<img src="https://public.readdy.ai/ai/img_res/f5a2f48db6be4ae772e5ced9745e1cc9.jpg" class="w-8 h-8 rounded-full mr-2" alt="Instructor">
<span class="text-sm text-gray-600">Dr. Michael Chen</span>
</div>
<span class="text-lg font-bold text-primary">₦89,550</span>
</div>
</div>
</a>
</div>
<a href="#course-details" class="block bg-white rounded-lg shadow-lg overflow-hidden course-card transition-all duration-300">
<img src="https://public.readdy.ai/ai/img_res/d56371f541df8ada0cde06719d0f5715.jpg" class="w-full h-48 object-cover" alt="Course Image">
<div class="p-6">
<div class="flex items-center justify-between mb-2">
<span class="px-3 py-1 text-xs font-medium text-primary bg-primary/10 rounded-full">Intermediate</span>
<span class="text-gray-600">8 weeks</span>
</div>
<h3 class="text-xl font-semibold mb-2">Data Structures Masterclass</h3>
<p class="text-gray-600 mb-4">Comprehensive guide to essential data structures</p>
<div class="flex items-center justify-between">
<div class="flex items-center">
<img src="https://public.readdy.ai/ai/img_res/5bd6e3f32def2cda2c2a8398436c0232.jpg" class="w-8 h-8 rounded-full mr-2" alt="Instructor">
<span class="text-sm text-gray-600">Prof. Sarah Johnson</span>
</div>
<span class="text-lg font-bold text-primary">₦67,050</span>
</div>
</div>
</a>
</div>
<a href="#course-details" class="block bg-white rounded-lg shadow-lg overflow-hidden course-card transition-all duration-300">
<img src="https://public.readdy.ai/ai/img_res/562f64c3676fbea1142ba3e4208e1369.jpg" class="w-full h-48 object-cover" alt="Course Image">
<div class="p-6">
<div class="flex items-center justify-between mb-2">
<span class="px-3 py-1 text-xs font-medium text-primary bg-primary/10 rounded-full">Beginner</span>
<span class="text-gray-600">10 weeks</span>
</div>
<h3 class="text-xl font-semibold mb-2">Cloud Computing Essentials</h3>
<p class="text-gray-600 mb-4">Introduction to modern cloud architectures</p>
<div class="flex items-center justify-between">
<div class="flex items-center">
<img src="https://public.readdy.ai/ai/img_res/d878f7527a2bb6c823895710e43d0094.jpg" class="w-8 h-8 rounded-full mr-2" alt="Instructor">
<span class="text-sm text-gray-600">David Williams</span>
</div>
<span class="text-lg font-bold text-primary">₦80,550</span>
</div>
</div>
</a>
</div>
</div>
</div>
</section>
<section id="resources" class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-12">Learning Resources</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-book-open-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Free E-Books</h3>
<p class="text-gray-600 mb-4">Access our collection of programming e-books covering various topics from basics to advanced concepts.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Browse Library →</a>
</div>
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-secondary/10 rounded-full mb-4">
<i class="ri-video-line text-secondary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Video Tutorials</h3>
<p class="text-gray-600 mb-4">Watch step-by-step video tutorials created by our expert instructors to enhance your learning.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Watch Now →</a>
</div>
<div class="bg-white p-6 rounded-lg shadow-lg">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mb-4">
<i class="ri-file-paper-2-line text-primary text-2xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Practice Problems</h3>
<p class="text-gray-600 mb-4">Challenge yourself with our curated collection of programming problems and exercises.</p>
<a href="#" class="text-primary hover:text-primary/90 font-medium">Start Practice →</a>
</div>
</div>
</a>
</div>
</section>
<section id="about" class="py-20 bg-gray-50">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="space-y-6">
<h2 class="text-3xl font-bold">About NUEL</h2>
<p class="text-gray-600">NUEL is a leading online platform dedicated to making computer science education accessible to everyone. Founded in 2023, we've helped over 20,000 students and growing. Computer science is an ever-evolving field that's becoming increasingly important for everyone. At NUEL, we make learning programming approachable and engaging for students from all backgrounds.</p>
<div class="space-y-4">
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Industry-relevant curriculum designed by experts</p>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Flexible learning schedule with lifetime access</p>
</div>
<div class="flex items-center">
<div class="w-8 h-8 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-check-line text-primary"></i>
</div>
<p class="text-gray-600">Dedicated support team available 24/7</p>
</div>
</div>
</a>
</div>
<div class="relative">
<img src="https://static.readdy.ai/image/3b38bec4fae1c2a1ea101ae1e09e7a1e/1fe1bbea2c200e53ff68f24c1de0daa0.png" class="rounded-lg shadow-xl object-cover w-full h-full" alt="About Computer Science Project">
</div>
</div>
</a>
</div>
</section>
<section id="contact" class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<div class="space-y-8">
<h2 class="text-3xl font-bold">Get in Touch</h2>
<p class="text-gray-600">Have questions about our courses or need help getting started? Our team is here to help you begin your learning journey.</p>
<div class="space-y-6">
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-map-pin-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Visit Us</h3>
<p class="text-gray-600">123 Tech Avenue, Silicon Valley, CA 94025</p>
</div>
</div>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-phone-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Call Us</h3>
<p class="text-gray-600">+1 (555) 123-4567</p>
</div>
</div>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full mr-4">
<i class="ri-mail-line text-primary text-xl"></i>
</div>
<div>
<h3 class="font-semibold">Email Us</h3>
<p class="text-gray-600">contact@computerscienceproject.com</p>
</div>
</div>
</a>
</div>
</div>
<form class="space-y-6 bg-gray-50 p-8 rounded-lg">
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Full Name</label>
<input type="text" class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary" placeholder="Enter your name">
</div>
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Email Address</label>
<input type="email" class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary" placeholder="Enter your email">
</div>
<div>
<label class="block text-sm font-medium text-gray-700 mb-2">Message</label>
<textarea class="w-full px-4 py-2 border border-gray-200 rounded-button focus:outline-none focus:border-primary h-32" placeholder="Enter your message"></textarea>
</div>
<button class="w-full px-6 py-3 text-white bg-primary hover:bg-primary/90 !rounded-button">Send Message</button>
</form>
</div>
</div>
</section>
<section class="py-20 bg-white">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-16">Why Choose Us</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-12">
<div class="text-center">
<div class="w-16 h-16 mx-auto flex items-center justify-center bg-primary/10 rounded-full mb-6">
<i class="ri-time-line text-primary text-3xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Learn at Your Pace</h3>
<p class="text-gray-600">Access course content 24/7 and learn at your own schedule with lifetime access to all materials.</p>
</div>
<div class="text-center">
<div class="w-16 h-16 mx-auto flex items-center justify-center bg-secondary/10 rounded-full mb-6">
<i class="ri-user-star-line text-secondary text-3xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Expert Instructors</h3>
<p class="text-gray-600">Learn from industry professionals with years of real-world experience in top tech companies.</p>
</div>
<div class="text-center">
<div class="w-16 h-16 mx-auto flex items-center justify-center bg-primary/10 rounded-full mb-6">
<i class="ri-code-box-line text-primary text-3xl"></i>
</div>
<h3 class="text-xl font-semibold mb-4">Hands-on Projects</h3>
<p class="text-gray-600">Build real-world projects and develop a portfolio that showcases your skills to employers.</p>
</div>
</div>
</a>
</div>
</section>
<section class="py-20 bg-gray-50">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<h2 class="text-3xl font-bold text-center mb-16">Student Success Stories</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
<div class="bg-white p-8 rounded-lg shadow-lg">
<div class="flex items-center mb-6">
<img src="https://public.readdy.ai/ai/img_res/f43ebe967404c2c26a681c6e5dac9083.jpg" class="w-12 h-12 rounded-full mr-4" alt="Student">
<div>
<h4 class="font-semibold">Emma Thompson</h4>
<p class="text-gray-600 text-sm">Software Engineer at Google</p>
</div>
</div>
<p class="text-gray-600">"The algorithms course completely transformed my problem-solving abilities. I landed my dream job at Google thanks to the skills I learned here."</p>
</div>
<div class="bg-white p-8 rounded-lg shadow-lg">
<div class="flex items-center mb-6">
<img src="https://public.readdy.ai/ai/img_res/9a18577116d584d28f318fac3a3c71f5.jpg" class="w-12 h-12 rounded-full mr-4" alt="Student">
<div>
<h4 class="font-semibold">James Rodriguez</h4>
<p class="text-gray-600 text-sm">Full Stack Developer at Microsoft</p>
</div>
</div>
<p class="text-gray-600">"The practical approach to learning and the support from instructors helped me transition from a non-tech background to a developer role."</p>
</div>
<div class="bg-white p-8 rounded-lg shadow-lg">
<div class="flex items-center mb-6">
<img src="https://public.readdy.ai/ai/img_res/8b724cb3e2d004c3181c1fe87400d04a.jpg" class="w-12 h-12 rounded-full mr-4" alt="Student">
<div>
<h4 class="font-semibold">Lisa Chen</h4>
<p class="text-gray-600 text-sm">Data Engineer at Amazon</p>
</div>
</div>
<p class="text-gray-600">"The cloud computing courses provided me with the exact skills I needed to advance my career. The hands-on projects were invaluable."</p>
</div>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
<div>
<h3 class="text-4xl font-bold text-primary mb-2">50,000+</h3>
<p class="text-gray-600">Enrolled Students</p>
</div>
<div>
<h3 class="text-4xl font-bold text-primary mb-2">92%</h3>
<p class="text-gray-600">Completion Rate</p>
</div>
<div>
<h3 class="text-4xl font-bold text-primary mb-2">85%</h3>
<p class="text-gray-600">Employment Rate</p>
</div>
<div>
<h3 class="text-4xl font-bold text-primary mb-2">45%</h3>
<p class="text-gray-600">Average Salary Increase</p>
</div>
</div>
</a>
</div>
</section>
<section class="py-20 bg-primary">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
<h2 class="text-3xl font-bold text-white mb-8">Take Your First Step!</h2>
<p class="text-xl text-white/90 mb-8 max-w-2xl mx-auto">Join our friendly community of beginner programmers and start your coding journey today. No experience needed!</p>
<button onclick="window.location.href='#courses'" class="px-8 py-4 text-lg bg-white text-primary hover:bg-gray-100 !rounded-button">Get Started Today</button>
</div>
</section>
</main>
<footer class="bg-gray-900 text-white py-12">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 md:grid-cols-4 gap-12">
<div>
<a href="#" class="text-2xl font-['Pacifico'] text-white mb-4 block">Computer Science Project</a>
<p class="text-gray-400">Making coding accessible and fun for everyone.</p>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Course Categories</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white">Programming</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Data Structures</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Algorithms</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Cloud Computing</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Support</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white">Help Center</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Student Resources</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Career Services</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Contact Us</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Newsletter</h3>
<p class="text-gray-400 mb-4">Subscribe to get updates on new courses and features.</p>
<div class="flex">
<input type="email" placeholder="Enter your email" class="flex-1 px-4 py-2 text-gray-900 rounded-l-button focus:outline-none">
<button class="px-4 py-2 bg-primary text-white rounded-r-button hover:bg-primary/90">Subscribe</button>
</div>
</div>
</a>
</div>
<div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
<p class="text-gray-400">&copy; 2025 ComputerScienceProject.com. All rights reserved.</p>
<div class="flex space-x-6 mt-4 md:mt-0">
<a href="#" class="text-gray-400 hover:text-white">
<i class="ri-facebook-fill text-xl"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<i class="ri-twitter-fill text-xl"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<i class="ri-linkedin-fill text-xl"></i>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<i class="ri-youtube-fill text-xl"></i>
</a>
</div>
</div>
</a>
</div>
</footer>
</body>
</html>
