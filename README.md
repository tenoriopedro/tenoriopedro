# Pedro Tenório

## Junior Data Engineer | Computer Engineering Student

Focused on building efficient data pipelines, out-of-core processing, and infrastructure optimization. My goal is to design data ingestion and transformation systems that operate predictably and resiliently, minimizing I/O and computational costs.

Currently completing a Bachelor's degree in Computer Engineering, while deepening my knowledge in distributed systems fundamentals, analytical database modeling, and Edge architectures.

<p align="left">
  <a href="https://www.linkedin.com/in/tenono-pedro" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:pstsouza13@gmail.com">
    <img src="https://img.shields.io/badge/Email-pstsouza13@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

### ⚙️ Engineering & Tools

*   **Languages & Formats:** Python (Strict Typing), SQL, Apache Parquet.
*   **Processing & I/O:** PyArrow, Pydantic, Out-of-Core Memory Management.
*   **Infrastructure & Deployment:** Linux (POSIX, Bash), Docker, AWS EC2, PostgreSQL.
*   **Machine Learning (Edge):** OpenVINO, YOLOv8, OpenCV (CPU/Integrated GPU Inference Optimization).

---

### 🚀 Architectural Projects

<details open>
  <summary>
    <strong>1. Traffic Telemetry Engine (Edge Computing)</strong>
  </summary>
  <br>
  <p>Data producer pipeline optimized for resource-constrained hardware. Transforms raw video into columnar structured events, preventing Out-Of-Memory (OOM) failures.</p>
  <ul>
    <li><strong>Architecture:</strong> Ingestion via OpenCV, native mathematical acceleration via OpenVINO, and memory buffer managed by PyArrow.</li>
    <li><strong>Engineering Decision:</strong> Decoupling the visual rendering layer. Vector data (Pydantic) is consolidated and serialized directly to disk in Parquet format, reducing thermal I/O cost on the Edge.</li>
  </ul>
  <p>
    <a href="https://github.com/tenoriopedro/vehicle-counter-YOLO" target="_blank">[ ➔ View Repository & Documentation ]</a>
  </p>
</details>

<br>

<details open>
  <summary>
    <strong>2. Advanced Python Laboratory & CPython Internals</strong>
  </summary>
  <br>
  <p>Repository focused on the internal mechanics of the language and strict software engineering patterns.</p>
  <ul>
    <li><strong>Focus:</strong> Package architecture, Tooling (uv, Ruff), strict static typing (Pyright/Mypy), and optimized data structures.</li>
    <li><strong>Goal:</strong> Abandon the basic syntax of isolated scripts and apply SOLID principles and encapsulation in modern Python code.</li>
  </ul>
  <p>
    <a href="https://github.com/tenoriopedro/Advanced-Python-Learning" target="_blank">[ ➔ Explore Laboratory ]</a>
  </p>
</details>

<br>

<details open>
  <summary>
    <strong>3. Movie Catalog API (Client-Server Architecture)</strong>
  </summary>
  <br>
  <p>Demonstration of relational modeling, strict validation, and data exposure via RESTful services.</p>
  <ul>
    <li><strong>Stack:</strong> Python, Django REST Framework, PostgreSQL, JWT, Docker.</li>
    <li><strong>Engineering Decision:</strong> Implementation of business rules at the model and serializer level, bulk ingestion scripts (CSV to DB), and container orchestration with dedicated volumes.</li>
  </ul>
  <p>
    <a href="https://github.com/tenoriopedro/flix_api" target="_blank">[ ➔ View API Source Code ]</a>
  </p>
</details>
