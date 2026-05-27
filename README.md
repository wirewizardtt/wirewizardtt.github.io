export default function WireWizardWebsite() {
  return (
    <div className="min-h-screen bg-gray-100 text-gray-800">
      {/* Hero Section */}
      <header className="bg-blue-900 text-white py-20 px-6 text-center">
        <h1 className="text-5xl font-bold mb-4">WireWizard</h1>
        <p className="text-xl mb-6">
          Professional Electrical & Plumbing Maintenance Services
        </p>
        <button className="bg-yellow-400 text-black px-6 py-3 rounded-2xl font-semibold shadow-lg hover:bg-yellow-300 transition">
          Book a Service
        </button>
      </header>

      {/* About Section */}
      <section className="py-16 px-6 max-w-6xl mx-auto grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 className="text-4xl font-bold mb-4">About WireWizard</h2>
          <p className="text-lg leading-relaxed">
            WireWizard is a trusted electrical and plumbing maintenance company
            providing residential, commercial, and industrial solutions. We
            specialize in installations, troubleshooting, repairs, and preventive
            maintenance.
          </p>
        </div>

        <div className="bg-white rounded-3xl shadow-xl p-8">
          <h3 className="text-2xl font-semibold mb-4">Why Choose Us?</h3>
          <ul className="space-y-3 text-lg">
            <li>✔ Certified Technicians</li>
            <li>✔ 24/7 Emergency Services</li>
            <li>✔ Reliable & Affordable Solutions</li>
            <li>✔ Residential & Commercial Expertise</li>
            <li>✔ Customer Satisfaction Guaranteed</li>
          </ul>
        </div>
      </section>

      {/* Services Section */}
      <section className="bg-white py-16 px-6">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-10">Our Services</h2>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-gray-100 p-8 rounded-3xl shadow-md hover:shadow-xl transition">
              <h3 className="text-2xl font-semibold mb-4">Electrical Services</h3>
              <p>
                Wiring, panel upgrades, lighting installation, fault finding,
                breaker replacement, and electrical maintenance.
              </p>
            </div>

            <div className="bg-gray-100 p-8 rounded-3xl shadow-md hover:shadow-xl transition">
              <h3 className="text-2xl font-semibold mb-4">Plumbing Services</h3>
              <p>
                Leak repairs, pipe installations, drain cleaning, water pumps,
                bathroom fixtures, and plumbing maintenance.
              </p>
            </div>

            <div className="bg-gray-100 p-8 rounded-3xl shadow-md hover:shadow-xl transition">
              <h3 className="text-2xl font-semibold mb-4">Maintenance Contracts</h3>
              <p>
                Scheduled inspections and preventive maintenance plans for homes,
                offices, and industrial facilities.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Ideal Client Section */}
      <section className="py-16 px-6 bg-gray-200">
        <div className="max-w-5xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-8">Who We Serve</h2>
          <div className="grid md:grid-cols-4 gap-6">
            <div className="bg-white p-6 rounded-2xl shadow">
              <h3 className="font-semibold text-xl mb-2">Homeowners</h3>
              <p>Safe and reliable home electrical & plumbing services.</p>
            </div>

            <div className="bg-white p-6 rounded-2xl shadow">
              <h3 className="font-semibold text-xl mb-2">Businesses</h3>
              <p>Prevent downtime with dependable maintenance support.</p>
            </div>

            <div className="bg-white p-6 rounded-2xl shadow">
              <h3 className="font-semibold text-xl mb-2">Property Managers</h3>
              <p>Efficient servicing for apartments and rental properties.</p>
            </div>

            <div className="bg-white p-6 rounded-2xl shadow">
              <h3 className="font-semibold text-xl mb-2">Industrial Clients</h3>
              <p>Heavy-duty maintenance and technical troubleshooting.</p>
            </div>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="bg-blue-900 text-white py-16 px-6 text-center">
        <h2 className="text-4xl font-bold mb-6">Contact WireWizard</h2>
        <p className="text-lg mb-3">📍 Trinidad & Tobago</p>
        <p className="text-lg mb-3">📞 +1 (868) 290-5953</p>
        <p className="text-lg mb-8">✉ lon_daly@hotmail.com.com</p>

        <button className="bg-yellow-400 text-black px-8 py-3 rounded-2xl font-bold shadow-lg hover:bg-yellow-300 transition">
          Request a Quote
        </button>
      </section>

      {/* Footer */}
      <footer className="bg-black text-white text-center py-6">
        <p>
          © 2026 WireWizard Electrical & Plumbing Maintenance Company. All
          Rights Reserved.
        </p>
      </footer>
    </div>
  );
}
# wirewizard.github.io
