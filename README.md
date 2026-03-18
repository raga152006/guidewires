# AI-Driven Parametric Income Protection for Gig Workers
##  Overview
Gig delivery workers (Zomato, Swiggy) depend on daily earnings, which are highly affected by external disruptions like weather, traffic, and city events.
This project proposes an **AI-based parametric insurance platform** that:
- Detects income drops
- Confirms external disruptions
- Triggers automatic payouts
---
##  Target Users
**Primary Users:** Delivery Partners  

**Example Profile:**
- Name: Arun  
- Platform: Swiggy  
- City: Chennai  
- Weekly Income: ₹5000  
- Work Hours: 5–6 hrs/day  

###  Pain Points
- Unpredictable earnings  
- No income protection  
- No disruption-based insurance  
---
##  Problem Statement
Delivery workers lose income due to:
- Weather conditions  
- Traffic congestion  
- Demand fluctuations  
But:
- No system exists for income-loss protection  
- Traditional insurance ignores this problem  
---
##  Solution
An **AI-driven parametric insurance system** using:

Income Drop + External Disruption → Automatic Payout
---
## System Architecture

Worker App
↓
Policy Management System
↓
Income Monitoring Engine
↓
AI Disruption Detection Model
↓
Data Sources:

Weather Data

Traffic Data

City Events
↓
Trigger Engine
↓
Fraud Detection
↓
Payout Engine (UPI)
---
##  Workflow
### 1. Worker Onboarding
- Worker ID  
- Location  
- Weekly income  
- Delivery zone  
### 2. Baseline Earnings
Example:
- Mon: ₹480  
- Tue: ₹520  
- Wed: ₹500  
Average = ₹500  
### 3. Data Collection
- Weather data  
- Traffic data  
- Demand patterns  
---
##  Income Detection
Example:
- Expected: ₹500  
- Actual: ₹200  
**Condition:**
Income Drop > 50%
---
##  Disruption Score

Score =
0.4 × Weather Severity +
0.3 × Traffic Congestion +
0.3 × Demand Drop
---
## Trigger Rule
Payout occurs when:
- Income drop > 50%  
- Disruption score exceeds threshold  
- Worker is active  
---
##  Fraud Detection
### Methods
- GPS validation  
- Activity verification  
- Behavioral analysis  
### Model
- Isolation Forest  
---
##  Pricing Model
| Risk Level | Premium | Coverage |
|------------|--------|----------|
| Low        | ₹20    | ₹500     |
| Medium     | ₹35    | ₹800     |
| High       | ₹50    | ₹1200    |

---
##  Example Scenario
- Expected Income: ₹500  
- Actual Income: ₹200  
- Loss: ₹300  
 **Payout: ₹300**
---
##  Tech Stack
- Backend: FastAPI (Python)  
- ML: Scikit-learn, XGBoost  
- Database: PostgreSQL  
- Frontend: React  
- APIs: Weather, Traffic  
- Payments: UPI  
---
##  Dashboard Features
- Disruption events  
- Payout history  
- Risk scores  
- Worker activity  
---
## Scalability
- Cloud: AWS / GCP  
- Streaming: Kafka  
- Periodic model retraining  
---
##  Impact
- Financial stability for gig workers  
- Instant automated payouts  
- Reduced income volatility 
---
##  Future Enhancements
- Platform integrations (Swiggy, Zomato)  
- Blockchain smart contracts  
- Advanced AI risk models  
- Disaster monitoring  
---
##  Anti-Fraud Strategy
### Genuine Pattern
- Gradual income drop  
- Real movement  
- Active working behavior  
- Matches external conditions  
### Fraud Pattern
- Sudden drop without activity  
- Fake GPS signals  
- No environmental correlation  
- Repeated claims  
---
##  Decision Logic
If (Income + Behavior + Environment Match)
→ Genuine → Payout
Else
→ Fraud → Flagged
---
##  Data Signals Used
### Mobility
- Speed  
- Route continuity  
### Device
- Device ID  
- Emulator detection  
### Network
- IP clustering  
- Latency  
### Behavior
- Order acceptance rate  
- Activity duration  
### Temporal
- Claim timing patterns  
### Cross-User
- Pattern similarity  
---
##  Models Used
- Isolation Forest  
- Graph Clustering  
- Time-Series Analysis  
---
##  UX Strategy
- Low Risk → Instant payout  
- Medium Risk → Delayed verification  
- High Risk → Manual review  
---
##  Fairness Features
- Partial payouts  
- Appeal system  
- Explainable alerts  
- Trust score system  
---
##  Outcome
- Fraud-resistant system  
- Fair payouts  
- Reduced false positives  
---
##  Innovation
Combines:
- Behavior  
- Environment  
- Device  
- Network  
 Creates a **robust AI-driven parametric insurance system**
---
##  Conclusion
This system reduces **basis risk** by combining:
- Multi-signal AI detection  
- Real income validation  
- Automated payouts  
---
