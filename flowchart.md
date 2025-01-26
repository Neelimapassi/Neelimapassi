'''mermaid
graph TD
    A[Child's Age: 90 days to 12 years] --> B[Policy Term: 25 years - Entry Age]
    B --> C[Premium Payment Term: 20 years - Entry Age]
    C --> D{Choose Option}
    D --> |Option 1| E[No Survival Benefit<br>100% Sum Assured at Maturity]
    D --> |Option 2| F[5% Sum Assured per year<br>75% Sum Assured at Maturity]
    D --> |Option 3| G[10% Sum Assured per year<br>50% Sum Assured at Maturity]
    D --> |Option 4| H[15% Sum Assured per year<br>25% Sum Assured at Maturity]
    E --> I[Maturity at Age 25]
    F --> I
    G --> I
    H --> I
    I --> J[Additional Benefits:<br>Bonuses & Tax Benefits] '''
