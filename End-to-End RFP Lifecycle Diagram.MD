flowchart TD

A[Stage 1: Trigger & Problem Recognition] --> B[Stage 2: Scoping & Alignment]
B --> C[Stage 3: Current-State Assessment]
C --> D[Stage 4: Future-State Vision]
D --> E[Stage 5: Sourcing Strategy]

E --> E1[Engagement Model]
E --> E2[Scope Packaging]
E --> E3[Commercial Model]
E --> E4[Vendor Criteria]

E --> F[Stage 6: RFI - Market Understanding]
F --> G[Stage 7: RFP Creation]
G --> H[Stage 8: Internal Review & Approval]
H --> I[Stage 9: RFP Release]

I --> J[Stage 10: Bidder Engagement]
J --> J1[Pre-Bid Conference]
J --> J2[Q&A Process]

J --> K[Stage 11: Proposal Submission]
K --> L[Stage 12: Evaluation]

L --> M[Vendor Selection & Transformation Start]

%% Styling
classDef stage fill:#f5f5f5,stroke:#333,stroke-width:1px;
class A,B,C,D,E,F,G,H,I,J,K,L,M stage;
