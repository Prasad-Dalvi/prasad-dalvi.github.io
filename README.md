🚀 AI-Powered Manufacturing Traceability System

Transforming fragmented factory data into real-time, intelligent decision-making.

📌 Problem Statement

In most manufacturing setups, tracing a defective product takes 3–5 days due to:

Disconnected Excel sheets
Manual record-keeping
Missing and inconsistent data

This delay leads to:

Continued shipment of defective products
Financial loss (₹ lakhs per recall)
Damage to OEM relationships
💡 Solution

We built a data-driven, AI-powered traceability system that:

Connects Raw Material → Production → QC → Dispatch
Works with real-world messy data
Provides instant traceability (<5 seconds)
Enables smart recall decisions
🧠 Key Features
🔍 1. Real-Time Traceability
Trace any order (e.g., D-1847) instantly
Get:
Raw material lot
Supplier
Machine & shift
QC results
🧩 2. Smart Data Linking Engine

Handles real-world data issues:

Missing batch IDs → inferred
Missing lot numbers → reconstructed
Inconsistent defect labels → normalized
Multi-batch dispatch → split and processed
🚨 3. Contamination Impact Analysis
Input defective lot (e.g., LOT-2023-114)
Instantly identify:
All affected batches
All orders
All customers
🔮 4. Risk Prediction System
Assigns risk levels (High / Medium / Low)
Based on:
QC defect rate
Supplier linkage
🚚 5. Actionable Recall Management
Shipment status:
Delivered / In Transit / Not Shipped
Priority tagging:
Urgent / Medium / Low
One-click recall report generation
⚙️ Tech Stack
Frontend: HTML, CSS, JavaScript
Data Processing: JavaScript (PapaParse)
Architecture: Client-side (Fully offline capable)
📂 Data Sources

The system works with the following CSV files:

raw_materials_log.csv
production_log.csv
qc_inspection.csv
dispatch_log.csv
supplier_master.csv
🔄 How It Works
Upload CSV files
Data is:
Cleaned
Normalized
Indexed
Linking engine connects:
Dispatch → Batch → Production → Lot → Supplier → QC
Queries return results in seconds
🧪 Demo Use Cases
✅ Trace Order

Input:

D-1847

Output:

Lot number
Supplier
Machine & shift
QC result
🚨 Contamination Alert

Input:

LOT-2023-114

Output:

Affected batches
Affected orders
Impacted customers
📊 Business Impact
Problem	Traditional	Our System
Trace time	3–5 days	< 5 seconds
Recall scope	Manual, error-prone	Instant & accurate
Data quality	Poor	Cleaned & inferred
Decision making	Delayed	Real-time
🎯 Key Innovation

“We don’t just connect data — we reconstruct missing reality.”

👷 User-Centric Design
Simple UI for shop-floor workers
Minimal input (dropdown-based)
Bilingual-ready (English/Marathi)
Offline-first architecture
🚀 Future Scope
Database integration (PostgreSQL / SQLite)
Real-time IoT integration
SMS/Email alert system
Advanced ML-based risk prediction
🏁 Conclusion

This system is not just a traceability tool —
it is a real-time decision system that helps industries:

Prevent defective shipments
Reduce recall costs
Protect customer relationships
