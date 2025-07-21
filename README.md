```mermaid
flowchart TD
   A[Start] --> B{Is the applicant 18 years old or older?}
   B -- No --> Z[Not Eligible]
   B -- Yes --> C{Is the applicant medically fit?}
   C -- No --> Z
   C -- Yes --> D{Is the applicant a Singapore Citizen, PR, or valid long-term pass holder?}
   D -- No --> Z
   D -- Yes --> E[Eligible to Apply as Driver]
