import React from "react";
export default function Portfolio() {
  return (
    <div className="p-8 max-w-4xl mx-auto font-sans">
      <h1 className="text-4xl font-bold mb-2">Thumma Nivas</h1>
      <p className="text-gray-600 mb-4">Aspiring AI/ML Engineer | B.Tech in Computer Science & AI/ML</p>
      <a
        href="/Resume.pdf"
        download
        className="inline-block mb-6 px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700"
      >
        📄 Download Resume
      </a>
      <section className="mb-8">
        <h2 className="text-2xl font-semibold">Projects</h2>
        <ul className="list-disc ml-6 mt-2 space-y-2">
          <li>
            <strong>Image Captioning (CNN + LSTM + Attention):</strong> Generated image captions using Flickr8k dataset and BLEU score.
          </li>
          <li>
            <strong>Online Payment Fraud Detection:</strong> Achieved 92% accuracy using Random Forest & XGBoost for transaction flagging.
          </li>
        </ul>
      </section>
      <section className="mb-8">
        <h2 className="text-2xl font-semibold">Internship</h2>
        <p>
          <strong>AWS Cloud Virtual Internship:</strong> Built ML-based chatbots, recommenders, and image classifiers using AWS AI services.
        </p>
      </section>
      <section className="mb-8">
        <h2 className="text-2xl font-semibold">Certifications</h2>
        <ul className="list-disc ml-6 mt-2">
          <li>Python — Cisco</li>
          <li>SQL — Oracle Dev</li>
          <li>GenAI — Google Cloud</li>
          <li>Soft Skills — NPTEL</li>
        </ul>
      </section>
      <section className="mb-8">
        <h2 className="text-2xl font-semibold">Technical Skills</h2>
        <p><strong>Languages:</strong> Python, C, SQL, Django (Basic)</p>
        <p><strong>Libraries:</strong> TensorFlow, Keras, PyTorch, Pandas, Matplotlib</p>
        <p><strong>Tools:</strong> Jupyter, VS Code, GitHub, Google Cloud</p>
      </section>
      <section className="mb-8">
        <h2 className="text-2xl font-semibold">Achievements</h2>
        <ul className="list-disc ml-6 mt-2">
          <li>⭐ 3-Star HackerRank (200+ problems solved)</li>
          <li>♟️ Inter-state Chess Team Player</li>
          <li>🏆 Participant in 10+ Hackathons</li>
        </ul>
      </section>
      <section>
        <h2 className="text-2xl font-semibold">Contact</h2>
        <p>Email: <a href="mailto:nivasthumma@gmail.com" className="text-blue-600">nivasthumma@gmail.com</a></p>
        <p>Phone: +91-6305623453</p>
        <p>LinkedIn: <a href="https://linkedin.com/in/thumma-nivas-178420259" target="_blank" className="text-blue-600">linkedin.com/in/thumma-nivas-178420259</a></p>
      </section>
    </div>
  );
}
