export default function QueenEstherWebsite() { return ( <div className="min-h-screen bg-gradient-to-b from-rose-100 to-red-200 text-gray-900 font-sans"> <header className="flex items-center justify-between px-8 py-6 bg-white/60 backdrop-blur-md shadow-md"> <h1 className="text-3xl font-bold text-rose-700">Queen Esther</h1> <nav className="space-x-6 text-lg"> <a href="#home" className="hover:text-rose-700">Home</a> <a href="#about" className="hover:text-rose-700">About</a> <a href="#gallery" className="hover:text-rose-700">Gallery</a> <a href="#contact" className="hover:text-rose-700">Contact</a> </nav> </header>

<section
    id="home"
    className="flex flex-col items-center justify-center text-center py-28 px-6"
  >
    <h2 className="text-6xl font-extrabold text-rose-800 drop-shadow-lg mb-6">
      Welcome to Queen Esther's World
    </h2>
    <p className="max-w-2xl text-xl text-gray-700 mb-8">
      A beautiful rose-themed website filled with elegance, love, style, and anime vibes.
    </p>
    <button className="bg-rose-700 hover:bg-rose-800 text-white px-8 py-4 rounded-2xl text-lg shadow-xl transition">
      Explore More
    </button>
  </section>

  <section id="about" className="px-8 py-20 bg-white/70 backdrop-blur-md">
    <div className="max-w-4xl mx-auto text-center">
      <h3 className="text-4xl font-bold text-rose-700 mb-6">About Queen Esther</h3>
      <p className="text-lg leading-8 text-gray-700">
        Queen Esther is a stylish and elegant personality with a love for beauty, fashion, anime, and creativity. This website was designed with soft rose colors and a romantic atmosphere to create a luxurious online presence.
      </p>
    </div>
  </section>

  <section id="gallery" className="px-8 py-20">
    <h3 className="text-4xl font-bold text-center text-rose-800 mb-12">Rose Gallery</h3>
    <div className="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      {[
        '🌹',
        '💖',
        '✨'
      ].map((item, index) => (
        <div
          key={index}
          className="bg-white rounded-3xl shadow-2xl p-12 flex items-center justify-center text-7xl hover:scale-105 transition"
        >
          {item}
        </div>
      ))}
    </div>
  </section>

  <section id="contact" className="bg-rose-800 text-white py-20 px-8 text-center">
    <h3 className="text-4xl font-bold mb-6">Contact Queen Esther</h3>
    <p className="text-lg mb-8">Connect and share love, creativity, and positivity.</p>
    <button className="bg-white text-rose-800 px-8 py-4 rounded-2xl text-lg font-semibold shadow-xl hover:bg-rose-100 transition">
      Send Message
    </button>
  </section>

  <footer className="text-center py-6 bg-rose-900 text-rose-100">
    © 2026 Queen Esther. All rights reserved.
  </footer>
</div>

); }
