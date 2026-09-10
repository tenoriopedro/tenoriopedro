# Pedro Tenório

## Data & Infrastructure Engineer

Data and Infrastructure Engineer specializing in building resilient pipelines and optimizing cloud environments. My core focus is bridging the gap between raw data ingestion and highly available infrastructure, ensuring that systems operate predictably while strictly minimizing AWS computational and I/O costs.

Currently managing production architectures, implementing secure Docker containerization, and automating CI/CD workflows to eliminate manual deployment risks. I prioritize scalable relational modeling (PostgreSQL/MySQL) and robust DataOps practices to protect system integrity and deliver tangible operational stability.

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
*   **Infrastructure & Deployment:** Linux (POSIX, Bash), Docker, AWS EC2, PostgreSQL/MySQL.
*   **Edge Analytics:** OpenVINO, YOLOv8, OpenCV (Inference Optimization).

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
    <strong>2. Relational Modeling & Bulk Ingestion Implementation</strong>
  </summary>
  <br>
  <p>Demonstration of strict relational database modeling, data integrity validation, and isolated infrastructure orchestration.</p>
  <ul>
    <li><strong>Stack:</strong> PostgreSQL, Python, Docker, ORM.</li>
    <li><strong>Engineering Decision:</strong> Implementation of business rules at the model level, execution of bulk ingestion scripts (CSV to DB), and container orchestration with persistent dedicated volumes to ensure data survival across rebuilds.</li>
  </ul>
  <p>
    <a href="https://github.com/tenoriopedro/flix_api" target="_blank">[ ➔ View Infrastructure Code ]</a>
  </p>
</details>

<br>

<details open>
  <summary>
    <strong>3. Advanced Python Laboratory</strong>
  </summary>
  <br>
  <p>Repository focused on the internal mechanics of the language and strict DataOps software engineering patterns.</p>
  <ul>
    <li><strong>Focus:</strong> Package architecture, Tooling (uv, Ruff), strict static typing (Pyright/Mypy), and optimized data structures.</li>
    <li><strong>Goal:</strong> Abandon basic scripting syntax to apply SOLID principles, encapsulation, and scalable system design.</li>
  </ul>
  <p>
    <a href="https://github.com/tenoriopedro/Advanced-Python-Learning" target="_blank">[ ➔ Explore Laboratory ]</a>
  </p>
</details>
