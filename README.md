# DataSage-AI
AI-Powered Metadata Intelligence &amp; Data Documentation Platform

# 📌 About the Project

In many organizations, databases grow rapidly but documentation doesn’t keep up. Over time, teams forget what tables mean, which columns are important, and which datasets are reliable. This creates confusion, slows down analytics, and reduces trust in data.

DataSage AI is our attempt to solve this problem.

We built a system that automatically connects to a database, extracts schema information, analyzes data quality, and uses AI to generate business-friendly documentation. Instead of reading raw technical metadata, users can understand their database in simple language and even ask questions through a chat interface.

Our goal is simple:
Make databases understandable, trustworthy, and accessible.

# 🚨 Problem Statement

Enterprise databases often suffer from:

1. Outdated or missing documentation

2. Technical descriptions that business users cannot understand

3. No visibility into data quality

4. Difficulty in identifying reliable datasets

5. Dependence on SQL expertise to explore data

Manual documentation takes time and quickly becomes obsolete. Teams need an automated and intelligent solution.

# 💡 Our Solution

DataSage AI provides:

1. Automatic schema extraction

2. Intelligent data profiling and quality scoring

3. AI-generated business summaries

4. Conversational querying of database schema

5. Sensitive column detection

Instead of static documentation, we create a dynamic, AI-enhanced data understanding system.

# 🏗 How the System Works

Our system follows a modular pipeline:

The database is connected securely.

Metadata such as tables, columns, primary keys, and relationships are extracted.

A profiling engine calculates metrics like null percentage, uniqueness, and data quality score.

An LLM generates business-friendly explanations and insights.

Documentation is stored and indexed using a vector database.

Users interact through a Flask-based dashboard and chat assistant.

This ensures that technical backend intelligence is delivered through a simple and intuitive interface.

# 🔍 Key Features
1️⃣ Automated Metadata Extraction

We extract:

- Table names

- Column details

- Primary and foreign keys

- Constraints

No manual effort required.

2️⃣ Intelligent Data Profiling

For each table, we compute:

- Null percentage

- Distinct count

- Completeness score

- Data Quality (DQ) score

This helps teams understand which datasets are reliable.

3️⃣ AI-Generated Documentation

Using LLMs, we convert raw schema into:

- Business summaries

- Use cases

- Risk analysis

- Data quality insights

Technical schema becomes readable and meaningful.

4️⃣ Conversational Chat Interface

Users can ask questions like:

- “Which table contains revenue data?”

- “Is the customer table reliable?”

- “Which columns have high null values?”

The system retrieves relevant documentation and responds intelligently.

5️⃣ SQL Generation (Optional Feature)

Users can generate SQL queries from natural language input, improving productivity for analysts.

6️⃣ Sensitive Data Detection

Columns that may contain emails, phone numbers, or personal identifiers are flagged for awareness.

# 🎨 UI/UX Prototype

We designed a clean and minimal interface focused on clarity.

The prototype includes:

- Login / Landing page

- Dashboard overview

- Tables list with DQ badges

- Data quality visualization screen

- AI documentation display page

- Chat assistant interface

The UI is structured to ensure business users can navigate easily without technical knowledge.

# ⚙️ Tech Stack

Backend:

- Flask

- SQLAlchemy

- Pandas

Database:

- PostgreSQL

AI:

- OpenAI API / LLM

- ChromaDB (Vector Store for semantic search)

Frontend:

- HTML

- Bootstrap

- JavaScript

# 🔮 Future Scope

This project can evolve into a full enterprise solution.

Possible extensions include:

- Multi-database support (Snowflake, SQL Server)

- Real-time data quality monitoring

- Schema change detection

- Data lineage visualization

- Role-based access control

- SaaS deployment model

With further development, this can become a scalable AI-powered metadata intelligence product.

# 🎯 Why This Project Matters

Data is only valuable when it is understood and trusted.

DataSage AI reduces manual documentation effort, increases data transparency, and bridges the gap between technical database schema and business understanding.

# 👥 Team

We are a two-member team:

- Member 1 – Focused on AI logic, profiling engine, and LLM integration

- Member 2 – Focused on system architecture, API design, and UI development

Together, we built both the intelligence layer and the user interface.
