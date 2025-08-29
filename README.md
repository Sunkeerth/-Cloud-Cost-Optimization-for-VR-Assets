# -Cloud-Cost-Optimization-for-VR-Assets
🌐 RGAC Virtual University – Hybrid Storage Strategy
📌 Overview

RGAC Virtual University adopts a decentralized hybrid storage model to drastically reduce cloud storage costs while keeping VR performance reliable.

Instead of storing all assets in expensive cloud servers, we leverage:

GitHub private repositories (free 1 GB/student) for Unity configs, prefabs, and lightweight assets.

Google Drive (15 GB/student free) for documents (certificates, PDFs, assignments).

Cloud platforms (AWS, GCP, Azure) only for heavy runtime assets like 3D models and videos.

👉 This hybrid approach cuts cloud costs by 55–60% at scale.

⚙️ How It Works
🛞 Real-World Analogy – Tire System Model

Outer Rubber (Shell) → Unity setup/config files stored on GitHub.

Inner Hub (Core) → Runtime Unity models hosted on cloud servers.

Impact Zone (Execution Trigger) → Unity simulations pull configs from GitHub + runtime assets from cloud.

Rotation (Execution) → VR platform runs seamlessly with reduced storage costs.

🔑 Storage Strategy

GitHub (Decentralized Asset Storage)

Each student creates 1 private repo (1 GB free).

With 200 students → 200 GB free decentralized storage.

Stores:

Unity configs (.json, .ini)

Shell scripts (.sh)

Lightweight prefabs, textures (<100 MB)

Secured via GitHub API tokens for RGAC systems only.

Google Drive (Student Docs)

Each student uses 1 GB of free Drive storage.

Uploads → PDFs, marksheets, certificates, assignments.

LMS stores only shareable links, not files.

Teachers click → Opens from Drive directly.

Cloud (Runtime Performance)

Heavy assets (3D models, VR videos, big prefabs) → stored in cloud (AWS/GCP/Azure).

Ensures fast, scalable VR execution.

📊 Cost Comparison
Cloud-Only Model (200 students, max load)

Storage: 250 GB

Bandwidth: 320 GB/month

Cost: ₹36,000 – ₹39,000 per year

Hybrid Model (GitHub + Drive + Cloud)

Storage: 50 GB (cloud only)

Bandwidth: 150 GB/month

Cost: ₹14,400 – ₹16,800 per year

👉 Savings = ~55–60% (~₹21,600/year saved for 200 students).

📈 Scalability & Break-Even
Students	Cloud-Only Cost	Hybrid Cost	Saving %
200	₹38,000	₹1,28,000	❌ Higher (overhead dominates)
1,000	₹1,80,000	₹2,00,000	❌ Higher
2,500	₹4,40,000	₹2,60,000	✅ 41% Cheaper
5,000	₹9,00,000	₹4,10,000	✅ 55% Cheaper
10,000	₹18,00,000	₹7,20,000	✅ 60% Cheaper

📍 Break-even point ≈ 2,200 students.

Below → Cloud-only cheaper.

Above → Hybrid model permanently cheaper (saves ₹10+ Lakhs/year at 10k students).

✅ Benefits

Cost Efficiency → Saves up to 60% cloud costs.

Scalability → Works better with 2,500+ students.

Security → GitHub (private repos) + Google Drive (encrypted).

Flexibility → Students manage their own repos & docs.

Performance → Cloud still handles runtime-heavy assets.

⚠️ Risks & Mitigation

Drive link privacy changes → Use LMS alerts if link invalid.

Account suspension (rare) → Students keep local backups.

Overhead maintenance (~₹1.1 Lakh/year) → Automate with DevOps to cut costs further.

🚀 Future Optimizations

DevOps Automation → Reduce overhead from ₹1.1 Lakh → ₹50k/year.

Quantum Encryption → For securing student data in cloud + GitHub repos.

Dynamic QR Codes → For document access & VR simulations.

📜 License

This project is maintained by RGAC Virtual University.
All rights reserved © 2025.
