import React from "react";
export default function Portfolio() {
  return (
    <div className="p-10 max-w-5xl mx-auto font-sans bg-white shadow-lg rounded-xl mt-10 text-gray-800">
      <header className="mb-10 text-center">
        <h1 className="text-5xl font-bold text-blue-700 mb-2">Thumma Nivas</h1>
        <p className="text-lg text-gray-500">Aspiring AI/ML Engineer | B.Tech in Computer Science & AI/ML</p>
        <a
          href="/Resume.pdf"
          download
          className="inline-block mt-4 px-6 py-2 bg-blue-600 text-white font-medium rounded hover:bg-blue-700 transition"
        >
          📄 Download Resume
        </a>
      </header>
      <section className="mb-10">
        <h2 className="text-3xl font-semibold border-b-2 border-blue-600 pb-1 mb-4">Projects</h2>
        <ul className="space-y-3 text-lg">
          <li>
            <strong>📷 Image Captioning:</strong> Used CNN + LSTM + Attention on Flickr8k dataset with BLEU scoring.
          </li>
          <li>
            <strong>💳 Fraud Detection:</strong> Achieved 92% accuracy using Random Forest & XGBoost on online transaction data.
          </li>
        </ul>
      </section>
      <section className="mb-10">
        <h2 className="text-3xl font-semibold border-b-2 border-blue-600 pb-1 mb-4">Internship</h2>
        <p className="text-lg">
          <strong>AWS Cloud Virtual Internship:</strong> Created ML-based solutions using AWS AI services like chatbots, classifiers, and recommendation engines.
        </p>
      </section>
      <section className="mb-10">
        <h2 className="text-3xl font-semibold border-b-2 border-blue-600 pb-1 mb-4">Certifications</h2>
        <ul className="list-disc ml-6 text-lg space-y-1">
          <li>Python — Cisco</li>
          <li>SQL — Oracle Dev</li>
          <li>GenAI — Google Cloud</li>
          <li>Soft Skills — NPTEL</li>
        </ul>
      </section>
      <section className="mb-10">
        <h2 className="text-3xl font-semibold border-b-2 border-blue-600 pb-1 mb-4">Technical Skills</h2>
        <ul className="text-lg space-y-1">
          <li><strong>Languages:</strong> Python, C, SQL, Django (Beginner)</li>
          <li><strong>Libraries:</strong> TensorFlow, Keras, PyTorch, Pandas, Matplotlib</li>
          <li><strong>Tools:</strong> Jupyter, GitHub, VS Code, Google Cloud</li>
        </ul>
      </section>
      <section className="mb-10">
        <h2 className="text-3xl font-semibold border-b-2 border-blue-600 pb-1 mb-4">Achievements</h2>
        <ul className="list-disc ml-6 text-lg space-y-1">
          <li>⭐ 3-Star HackerRank (200+ problems solved)</li>
          <li>♟️ Inter-state Chess Team Player</li>
          <li>🏆 Participated in 10+ Hackathons</li>
        </ul>
      </section>
      <footer className="text-center mt-10 text-gray-600">
        <h2 className="text-2xl font-semibold mb-2">Contact</h2>
        <p>Email: <a href="mailto:nivasthumma@gmail.com" className="text-blue-600 hover:underline">nivasthumma@gmail.com</a></p>
        <p>Phone: +91-6305623453</p>
        <p>LinkedIn: <a href="https://linkedin.com/in/thumma-nivas-178420259" target="_blank" className="text-blue-600 hover:underline">linkedin.com/in/thumma-nivas-178420259</a></p>
      </footer>
    </div>
  );
}
