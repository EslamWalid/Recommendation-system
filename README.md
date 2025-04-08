🛍️ Content-Based Recommendation System with Sentence Transformers & HNSW
This project presents a fast and scalable product recommendation system built on Amazon product data. By leveraging Sentence Transformers for semantic embeddings and HNSW (Hierarchical Navigable Small World) graphs for efficient similarity search, the system delivers real-time content-based recommendations.

🔍 Key Features:
Combined product name, main_category, and sub_category into a unified textual feature.

Used paraphrase-MiniLM-L6-v2 from sentence-transformers to generate dense vector embeddings.

Applied HNSWlib to build a high-performance similarity search index for fast product retrieval.

Trained on a large multi-category Amazon product dataset merged from multiple CSVs.

⚡ Performance:
Capable of performing real-time product recommendations with low-latency vector search.

Designed for scalability—efficient even on datasets with tens of thousands of products.

📂 Dataset:
Pulled from multiple Amazon product CSVs.

Categories include Electronics, Car Accessories, Sports, and more.

🛠️ Tech Stack:
sentence-transformers for semantic embeddings.

hnswlib for vector indexing.

pandas, NumPy, and Matplotlib for preprocessing and analysis.

🖥️ Use Case:
E-commerce platforms to suggest similar or complementary products.

Personalized search and browsing experiences based on semantic product similarity.
