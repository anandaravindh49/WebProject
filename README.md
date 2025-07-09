</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elegantra Interiors</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script defer src="scripts.js"></script>
</head>
<body class="font-serif text-gray-800 bg-[#f9f5f1] scroll-smooth">

  <!-- Hero Section -->
  <section class="relative h-screen bg-cover bg-center flex items-center justify-center text-white" style="background-image: url('assets/images/hero.jpg');">
    <div class="text-center bg-black bg-opacity-40 p-10 rounded">
      <h1 class="text-5xl font-bold">Elegantra Interiors</h1>
      <p class="text-xl mt-4 italic">Designing Your Dream Spaces</p>
      <a href="#contact" class="mt-6 inline-block bg-[#a47148] hover:bg-[#8b5e3c] text-white py-3 px-6 rounded transition">Book a Consultation</a>
    </div>
  </section>

  <!-- About Us -->
  <section class="py-20 px-8 bg-white text-center" id="about">
    <h2 class="text-3xl font-semibold mb-6">About Us</h2>
    <p class="max-w-2xl mx-auto">With over 5 years of experience, Elegantra Interiors brings warmth, style, and functionality to every space. We specialize in Residential, Commercial, and Modular Design solutions tailored to your needs.</p>
  </section>

  <!-- Services -->
  <section class="py-20 px-8 bg-[#f5eee8] text-center" id="services">
    <h2 class="text-3xl font-semibold mb-10">Our Services</h2>
    <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto">
      <div><img src="assets/icons/living-room.svg" class="mx-auto mb-4 h-16" /><p>Living Room Design</p></div>
      <div><img src="assets/icons/kitchen.svg" class="mx-auto mb-4 h-16" /><p>Kitchen Remodeling</p></div>
      <div><img src="assets/icons/office.svg" class="mx-auto mb-4 h-16" /><p>Office Interiors</p></div>
    </div>
  </section>

  <!-- Portfolio -->
  <section class="py-20 px-8" id="portfolio">
    <h2 class="text-3xl font-semibold text-center mb-10">Our Work</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
      <img src="assets/images/gallery1.jpg" class="rounded shadow" />
      <img src="assets/images/gallery2.jpg" class="rounded shadow" />
      <img src="assets/images/gallery3.jpg" class="rounded shadow" />
      <img src="assets/images/gallery4.jpg" class="rounded shadow" />
      <img src="assets/images/gallery5.jpg" class="rounded shadow" />
      <img src="assets/images/gallery6.jpg" class="rounded shadow" />
    </div>
  </section>

  <!-- Testimonials -->
  <section class="py-20 px-8 bg-[#f5eee8]" id="testimonials">
    <h2 class="text-3xl font-semibold text-center mb-10">What Our Clients Say</h2>
    <div class="max-w-4xl mx-auto grid gap-10 md:grid-cols-3 text-center">
      <div><img src="assets/images/client1.jpg" class="rounded-full w-20 h-20 mx-auto mb-4" /><p class="italic">“Elegantra transformed our home into a masterpiece.”</p><p class="mt-2 font-bold">– Priya N.</p></div>
      <div><img src="assets/images/client2.jpg" class="rounded-full w-20 h-20 mx-auto mb-4" /><p class="italic">“Creative, professional, and efficient!”</p><p class="mt-2 font-bold">– Arjun M.</p></div>
      <div><img src="assets/images/client3.jpg" class="rounded-full w-20 h-20 mx-auto mb-4" /><p class="italic">“Highly recommend for commercial spaces.”</p><p class="mt-2 font-bold">– Sneha R.</p></div>
    </div>
  </section>

  <!-- Contact -->
  <section class="py-20 px-8" id="contact">
    <h2 class="text-3xl font-semibold text-center mb-10">Get in Touch</h2>
    <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-10">
      <form class="space-y-4">
        <input type="text" placeholder="Name" class="w-full p-3 border border-gray-300 rounded" required />
        <input type="email" placeholder="Email" class="w-full p-3 border border-gray-300 rounded" required />
        <input type="tel" placeholder="Phone" class="w-full p-3 border border-gray-300 rounded" required />
        <textarea placeholder="Message" class="w-full p-3 border border-gray-300 rounded h-32"></textarea>
        <button type="submit" class="bg-[#a47148] text-white px-6 py-3 rounded hover:bg-[#8b5e3c]">Send Message</button>
      </form>
      <div>
        <p class="mb-2"><strong>Address:</strong> 123 Elegantra Street, Chennai, India</p>
        <p class="mb-2"><strong>Phone:</strong> +91-9876543210</p>
        <p class="mb-4"><strong>Email:</strong> contact@elegantra.com</p>
        <!-- Optional Google Map Embed -->
        <!-- <iframe src="..." width="100%" height="250" allowfullscreen></iframe> -->
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-[#eee0d1] py-8 text-center text-sm">
    <p>&copy; 2025 Elegantra Interiors. All rights reserved.</p>
    <div class="flex justify-center mt-4 space-x-4">
      <a href="#"><img src="assets/icons/instagram.svg" alt="Instagram" class="h-6" /></a>
      <a href="#"><img src="assets/icons/facebook.svg" alt="Facebook" class="h-6" /></a>
    </div>
    <!-- Optional Instagram feed preview -->
  </footer>
