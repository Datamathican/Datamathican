
### A little more about me...

```python
class Datamathican:
    def __init__(self):
        self.name = "Pramod"
        self.background = ["Mathematics of Data", "Science of Modeling"]
        self.current_focus = "Engineering & Scalability"
        self.location = "London, UK"
        
    def current_projects(self):
        return {
            "Work": "Migrating legacy financial scripts to Airflow DAGs",
            "Personal": "Real-time crypto-data ingestion (Kafka + Postgres)",
            "Learning": "Mastering IaC with Terraform"
        }

    def ask_me_about(self):
        topics = [
            "Why E(X) matters in Finance",
            "The Analyst to Engineer transition",
            "Best hiking trails within 2 hours of London 🥾"
        ]
        print(topics)

me = Datamathican()
print(f"Building the 'plumbing' to ensure data is clean, consistent, and fast.")
