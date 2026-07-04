class VigneshS:
    def __init__(self):
        self.name = "Vignesh S"
        self.title = "Power BI Developer | Data Analyst"
        self.location = "Chennai, India"
        self.certification = "Microsoft Certified: Power BI Data Analyst Associate (PL-300)"
        self.degree = "B.E, Mookambigai College of Engineering (2017 - 2021)"

        self.stack = {
            "bi_tools": ["Power BI", "DAX", "Power Query (M)", "Microsoft Fabric", "Tabular Editor"],
            "cloud_etl": ["Azure Data Factory", "Azure Databricks", "Azure Synapse Analytics", "ADLS Gen2"],
            "databases": ["Snowflake", "SQL Server", "PostgreSQL"],
            "languages": ["SQL", "Python", "DAX", "M"],
            "automation": ["Power Automate", "CI/CD Deployment Pipelines"],
        }

        self.currently_learning = ["Microsoft Fabric (Advanced)", "PySpark", "Azure Synapse Optimization"]
        self.fun_fact = "I once cut a 1-hour manual report down to 15 minutes ⚡"

    def motto(self) -> str:
        return "Clean data, clear dashboards, confident decisions."


if __name__ == "__main__":
    me = VigneshS()
    print(me.motto())
