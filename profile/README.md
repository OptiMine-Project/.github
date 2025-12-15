# OptiMine: Mining Insights, Maximizing Value
Asah Capstone Project for Mining Value Chain Optimization 

## Project Overview
OptiMine merupakan website yang dibuat untuk membantu optimalisasi rantai pasok penambangan batu bara khususnya pada bagian perencanaan tambang dan perencanaan pengiriman pasca tambang. Website ini memberikan rekomendasi prediksi dan rekomendasi perencanaan penambangan dan pengiriman output tambang berdasarkan data menggunakan kolaborasi antara Machine Learning dan Agentic AI. 

## Background
Industri pertambangan batubara merupakan salah satu bidang industri yang tergolong tradisional dan konservatif dalam hal inovasi meskipun memiliki banyak tantangan besar dalam prosesnya. Salah satu tantangan terbesarnya ada pada efektivitas rantai pasok yang belum maksimal. Berdasarkan Jurnal Weather Delay Cost to Trucking, oleh Daniel Krechmer, et al., biaya keterlambatan yang disebabkan oleh ketidaktentuan cuaca di US sebesar 8.659 USD, atau sekitar 1.6% dari total pasar angkutan barang US. Industri pertambangan batubara sering kali tidak berjalan sesuai dengan target yang telah direncanakan dikarenakan variabel di lapangan yang sering berubah dan sulit diprediksi. Kondisi tersebut menyebabkan proses penambangan dan pendistribusian menjadi terhambat dan alat berat mengalami kerusakan.

## Key Features 
1. **Rekomendasi Perencanaan** - Memberikan rekomendasi perencanaan dan justifikasi yang digunakan satu minggu ke depan berdasarkan data.
2. **ChatBox interaktif** - Kolom chatbox menjawab pertanyaan user seputar rekomendasi.

## Side Features 
1.  **User Registration** - User dapat login dengan akun masing-masing sehingga memiliki _personalized recommendations_ dengan dua tipe user (mine planner dan shipping planner)
3.  **Light/Dark Theme** - Dua tipe tema website sesuai dengan selera dan kebutuhan pengguna.
4.  **Language Options** - Dua tipe bahasa yang digunakan (Indonesia/English) sesuai kebutuhan dan preferensi pengguna.
5.  **Smart General ChatBox** - Chatbox untuk pertanyaan user secara general tanpa hasil rekomendasi sebelumnya. 
6.  **Dashboard Data** - Penyajian dashboard rangkuman informasi dari data yang telah dikumpulkan.

## Project Goals 
- Memudahkan optimasi perencanaan tambang dan pengiriman dengan rekomendasi berdasarkan data.
- Monitoring laporan progress lebih mudah dengan dashboard.

## Team Members and Roles
| Role        | ID Asah      | Nama    | Universitas  | GitHub Profile  |
| :---:       | :---:        | :---:   | :---:        | :---:           |
| Back-End    | F183D5Y1450  | Nandana Ayudya Natasaskara | AMIKOM Yogyakarta | [nandana05-tech](https://github.com/nandana05-tech) |
| Front-End   | F183D5Y1353  | Muhammad Rama Setama | AMIKOM Yogyakarta | [ramasaetamaa](https://github.com/ramasaetamaa)| 
| Front-End   | F183D5Y0481  |  Dicky Firdha Firmansyah | AMIKOM Yogyakarta | [Firdhabungg](https://github.com/Firdhabungg)|
| Machine Learning| M004D5X1615 | Rafidah Khoirun Nisa' | ITS Surabaya | [rafeeedah](https://github.com/rafeeedah) |
| Machine Learning| M004D5X1552 | Oryza Sative | ITS Surabaya | [oryzava](https://github.com/oryzava) |

## Repositories

- [**OptiMine Machine Learning**](https://github.com/OptiMine-Project/mining-ml)  
  Contains datasets, feature engineering logic, trained machine learning models, evaluation results, and inference pipelines for mining production, weather forecasting, and logistics optimization.

- [**OptiMine Backend Service**](https://github.com/OptiMine-Project/backendMiningV)  
  Backend service responsible for API orchestration, model inference handling, data flow management, and integration between ML outputs and AI reasoning layers.

- [**OptiMine Retrieval-Augmented Generation (RAG)**](https://github.com/OptiMine-Project/ragMining)  
  AI layer that combines ML outputs with domain knowledge to generate contextual explanations, recommendations, and decision support through an interactive chat interface.
  
- [**OptiMine Frontend (Web UI)**](https://github.com/OptiMine-Project/optimine-ui)  
  Web-based user interface for OptiMine, providing data visualization, scenario input, interactive dashboards, and AI-driven recommendations.

## Technology Stack 
- Machine Learning
   * Framework          : Scikit-Learn
   * IDE                : Google Colab
   * Libraries          : Numpy, Pandas, XGBoost, Scikit-optimize (skopt), Matplotlib, Seaborn
- Back-End
  * Framework           : FastAPI, Hapi.js
  * Runtime             : Node.js 
- Front-End
  * Core Technologies   : HTML5, CSS3, JavaScript (ES6+)
  * CSS Framework       : Tailwind CSS (CDN)
  * Visualization & UI  : Chart.js, Lucide Icons
  * Build Tool          : Webpack 5 + Dev Server
