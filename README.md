graph TD;
  actor User
  actor System
  usecase UserRegistration as "User Registration"
  usecase DataAnalysis as "Data Analysis"
  usecase RecommendationGeneration as "Recommendation Generation"
  usecase ResultDisplay as "Result Display"

  User -->|Interacts with| System
  User -->|Uses| UserRegistration
  User -->|Uses| DataAnalysis
  User -->|Uses| RecommendationGeneration
  System -->|Manages| ResultDisplay
