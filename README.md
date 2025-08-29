🌐 Cloud Cost Optimization for VR Assets

RGAC Virtual University – Hybrid Storage Strategy

📌 Overview

Traditional cloud storage for VR/AR platforms is expensive and inefficient when scaled across thousands of students.
RGAC Virtual University introduces a decentralized hybrid storage model that reduces cloud storage costs by 55–60% while maintaining high performance and scalability.

Instead of storing all assets on costly cloud servers, we leverage:

🗄 GitHub private repositories (1 GB/student free) → configs, prefabs, lightweight Unity assets
📂 Google Drive (15 GB/student free) → student documents (certificates, PDFs, assignments)
☁️ Cloud platforms (AWS/GCP/Azure) → runtime-heavy assets (3D models, videos, prefabs)
👉 This hybrid strategy saves lakhs of rupees annually at scale while improving flexibility.

🛞 How It Works (Tire System Model) :
    ┌──────────────────────────────┐
   │   Outer Rubber (Shell)       │ → Unity configs & scripts → GitHub  
   └──────────────────────────────┘
                 │
                 ▼
   ┌──────────────────────────────┐
   │   Inner Hub (Core)           │ → 3D Models, VR assets → Cloud (AWS/GCP/Azure)  
   └──────────────────────────────┘
                 │
                 ▼
   ┌──────────────────────────────┐
   │   Impact Zone (Execution)    │ → Unity simulation triggers GitHub + Cloud merge  
   └──────────────────────────────┘
                 │
                 ▼
   ┌──────────────────────────────┐
   │   Rotation (Runtime)         │ → VR runs smoothly at reduced storage cost  
   └──────────────────────────────┘

   🔑 Storage Strategy:
   
1️⃣ GitHub – Decentralized Asset Storage :

✔️ Each student creates 1 private repo (1 GB free)
✔️ With 200 students → 200 GB free storage
✔️ Stores:
Unity configs (.json, .ini)
Shell scripts (.sh)
Prefab metadata & lightweight textures (<100 MB)
✔️ Access controlled via GitHub API tokens

2️⃣ Google Drive – Student Documents :

✔️ Each student uses 1 GB from their free 15 GB quota
✔️ Stores: PDFs, certificates, assignments
✔️ LMS keeps links only, not files
✔️ Teacher → Click link → Opens securely in Drive
✔️ Security handled by Google (encryption + access control)

3️⃣ Cloud – Runtime Performance : 

✔️ Large runtime assets stored in cloud:
Full 3D models
VR videos
Heavy prefabs
✔️ Ensures speed + scalability

📊 Cost Comparison :

| Model          | Storage | Bandwidth (Monthly) | Annual Cost       |
| -------------- | ------- | ------------------- | ----------------- |
| **Cloud-Only** | 250 GB  | 320 GB              | ₹36,000 – ₹39,000 |
| **Hybrid**     | 50 GB   | 150 GB              | ₹14,400 – ₹16,800 |

📈 Scalability & Break-Even :

| Students | Cloud-Only Cost | Hybrid Cost | Saving %                      |
| -------- | --------------- | ----------- | ----------------------------- |
| 200      | ₹38,000         | ₹1,28,000   | ❌ Higher (overhead dominates) |
| 1,000    | ₹1,80,000       | ₹2,00,000   | ❌ Higher                      |
| 2,500    | ₹4,40,000       | ₹2,60,000   | ✅ 41% Cheaper                 |
| 5,000    | ₹9,00,000       | ₹4,10,000   | ✅ 55% Cheaper                 |
| 10,000   | ₹18,00,000      | ₹7,20,000   | ✅ 60% Cheaper                 |

📍 Break-even point ≈ 2,200 students
Below → Cloud-only cheaper
Above → Hybrid model saves ₹10+ Lakhs/year

✅ Benefits : 

✔️ Cost Efficiency → Save up to 60% in cloud costs
✔️ Scalability → Works better with 2,500+ students
✔️ Security → GitHub private repos + Google Drive encryption
✔️ Flexibility → Students manage their own repos & docs
✔️ Performance → Cloud still handles runtime-heavy assets

⚠️ Risks & Mitigation:

🔒 Drive link privacy issues → LMS alerts if link broken
📉 Account suspension (rare) → Students keep backups
💰 Overhead cost (~₹1.1 Lakh/year) → Mitigate with DevOps automation (~₹50k/year)

🚀 Future Optimizations:

🤖 DevOps Automation → Reduce operational overhead
🔐 Quantum Encryption → For GitHub + Cloud data security
🔗 Dynamic QR Codes → For secure doc & VR simulation access

📜 License

Maintained by RGAC Virtual University
All rights reserved © 2025



