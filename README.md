# Digital-Content-Scoring-Engine
Object‑oriented scoring engine for digital content. Demonstrates inheritance, method overriding, and polymorphism.

It models how different types of content (blog posts, videos) convert to engagement and reach based on their metrics.

The goal is to demonstrate OOP fundamentals (inheritance, method overriding, and polymorphism) in a digital marketing work case.

---

Features

- Base class `ContentItem` with shared attributes:
  - `metrics`: tuple of numerical performance indicators  
  - `quality_score`: qualitative score of the content  
- Derived classes:
  - `BlogPost`
  - `VideoContent`
- Each derived class implements:
  - `engagement_score()`
  - `reach_score()`
  - Custom `__repr__()` for readable output



