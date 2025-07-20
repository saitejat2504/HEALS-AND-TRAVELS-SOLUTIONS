<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heal with Travel | Affordable Surgeries & Indian Wellness Travel</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    body {
      scroll-behavior: smooth;
    }
    .gradient-bg {
      background: linear-gradient(135deg, #1e3a8a, #2563eb);
    }
    .section-title {
      @apply text-3xl md:text-4xl font-extrabold text-center text-blue-800 mb-6;
    }
    .card {
      @apply p-6 bg-white shadow-lg rounded-2xl hover:shadow-xl transition duration-300;
    }
    .cta-button {
      @apply mt-6 inline-block bg-white text-blue-700 px-6 py-3 rounded-full font-bold shadow hover:bg-blue-100;
    }
    .input-field {
      @apply p-3 rounded border border-blue-300 focus:outline-none focus:ring-2 focus:ring-blue-500;
    }
    .table-style th, .table-style td {
      @apply p-4 border;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">
  <script>AOS.init();</script>

  <!-- Hero Section -->
  <header class="gradient-bg text-white p-16 text-center" data-aos="fade-down">
    <img src="logo.png" alt="Heal with Travel Logo" class="mx-auto mb-6 w-24 h-24 rounded-full border-4 border-white shadow-lg">
    <h1 class="text-5xl font-extrabold mb-4">Heal with Travel</h1>
    <p class="text-xl md:text-2xl max-w-2xl mx-auto">Affordable Medical Surgeries + Beautiful Indian Recovery Tours</p>
    <a href="#quote" class="cta-button">Get a Free Quote</a>
  </header>

  <!-- Why India Section -->
  <section class="p-12 bg-white">
    <h2 class="section-title" data-aos="fade-up">Why Choose India for Medical Treatment?</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="card" data-aos="zoom-in" data-aos-delay="100">
        <h3 class="text-lg font-bold text-blue-700 mb-2">70% Lower Costs</h3>
        <p>Save thousands compared to U.S. healthcare prices.</p>
      </div>
      <div class="card" data-aos="zoom-in" data-aos-delay="200">
        <h3 class="text-lg font-bold text-blue-700 mb-2">World-Class Doctors</h3>
        <p>Be treated by experienced, internationally-trained specialists.</p>
      </div>
      <div class="card" data-aos="zoom-in" data-aos-delay="300">
        <h3 class="text-lg font-bold text-blue-700 mb-2">Incredible Tourism</h3>
        <p>Recover in destinations like Kerala, Goa, or the Himalayas.</p>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="p-12 bg-blue-50">
    <h2 class="section-title" data-aos="fade-up">Our Services</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="card" data-aos="fade-up" data-aos-delay="100">
        <h3 class="font-bold text-lg text-blue-700 mb-2">Surgery Scheduling</h3>
        <p>We coordinate appointments with India's top hospitals.</p>
      </div>
      <div class="card" data-aos="fade-up" data-aos-delay="200">
        <h3 class="font-bold text-lg text-blue-700 mb-2">Travel & Stay</h3>
        <p>Flight booking, visa help, and comfortable accommodations.</p>
      </div>
      <div class="card" data-aos="fade-up" data-aos-delay="300">
        <h3 class="font-bold text-lg text-blue-700 mb-2">Tourism & Recovery</h3>
        <p>Explore India while you heal—yoga retreats, sightseeing, and more.</p>
      </div>
    </div>
  </section>

  <!-- Cost Comparison -->
  <section class="p-12 bg-white">
    <h2 class="section-title" data-aos="fade-up">Sample Cost Comparison</h2>
    <div class="overflow-x-auto" data-aos="fade-up">
      <table class="table-auto w-full border-collapse shadow-md rounded-xl table-style">
        <thead class="bg-blue-200 text-blue-900">
          <tr>
            <th>Procedure</th>
            <th>U.S. Average</th>
            <th>India Average</th>
          </tr>
        </thead>
        <tbody class="bg-white text-gray-700">
          <tr>
            <td>Knee Replacement</td>
            <td>$50,000</td>
            <td>$7,000</td>
          </tr>
          <tr class="bg-gray-100">
            <td>Heart Bypass</td>
            <td>$120,000</td>
            <td>$15,000</td>
          </tr>
          <tr>
            <td>Dental Implants</td>
            <td>$4,000</td>
            <td>$800</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="quote" class="p-12 bg-blue-100">
    <h2 class="section-title" data-aos="fade-up">Request a Free Consultation</h2>
    <form class="max-w-xl mx-auto grid grid-cols-1 gap-5" data-aos="zoom-in">
      <input type="text" placeholder="Full Name" class="input-field">
      <input type="email" placeholder="Email Address" class="input-field">
      <input type="text" placeholder="Procedure Interested In" class="input-field">
      <textarea rows="4" placeholder="Tell us about your needs..." class="input-field"></textarea>
      <button type="submit" class="bg-blue-700 text-white py-3 rounded-xl font-semibold hover:bg-blue-800 transition duration-300">Submit Request</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center p-6 mt-12">
    <p class="text-sm">&copy; 2025 Heal with Travel. All rights reserved.</p>
  </footer>
</body>
</html>
