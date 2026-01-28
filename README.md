## Business Simulation: Investment & Logistics Decision Analysis

This project was developed as part of the **MSc in Business Analytics (BI Oslo)** for the course **GRA4138 – Business Simulation Analysis**.  
It applies **simulation modeling techniques** to support decision-making under uncertainty, combining **Monte Carlo Simulation** and **Agent-Based Modeling (AnyLogic)**.

The project is divided into two main parts:
1. A **Monte Carlo simulation** to evaluate long-term vineyard investment alternatives.
2. An **agent-based simulation** to analyze and optimize a perishable goods distribution network.

---

## Project Structure

business_simulation_project/
│
├── FINALEXAMMODELANYLOGIC.alp
│ Final AnyLogic agent-based simulation model.
│
├── FINALEXAMMODELANYLOGIC.original.alp
│ Original version of the AnyLogic model.
│
├── data.xlsx
│ Input data used for the simulation models.
│
├── db.data
├── db.properties
├── db.script
│ Internal database files used by AnyLogic.
│
├── giscache*
│ GIS cache files used for geographic routing and visualization.
│
└── Business_Simulation_FinalReport.pdf
Final academic report with methodology, results, and recommendations.


---

## Summary

### Part A – Monte Carlo Simulation (Vineyard Investment)
- Evaluated **five vineyard investment alternatives** over a 20-year horizon.
- Simulated uncertainty in yields, prices, demand, costs, and disease risk.
- Estimated **Net Present Value (NPV)** distributions using 1,000 simulations per alternative.
- Identified the optimal strategy for both **risk-neutral and risk-averse investors**.

### Part B – Agent-Based Simulation (Logistics & Distribution)
- Built an **agent-based model in AnyLogic** for a perishable dairy distribution network.
- Modeled interactions between **retailers, distributors, and truck fleets**.
- Analyzed delivery delays, spoilage, fleet utilization, routing efficiency, and total costs.
- Tested scenarios including warehouse expansion, fleet resizing, and demand shocks.
- Derived operational and strategic recommendations for logistics optimization.

---

## Key Insights

- Monte Carlo simulation is effective for evaluating **investment risk and uncertainty**.
- Combined grape varieties with modern farming techniques yield the **highest and most stable NPV**.
- In logistics, **fleet size and routing strategy** are major drivers of service level and cost.
- Opening new warehouses is not cost-effective without sufficient demand growth.
- Dynamic inventory and delivery policies significantly reduce spoilage and delays.

---

## Tools & Methods

- **Simulation Techniques:**  
  - Monte Carlo Simulation  
  - Agent-Based Modeling (ABM)

- **Software & Tools:**  
  - AnyLogic  
  - Excel  
  - GIS-based routing

- **Concepts:**  
  - Risk analysis  
  - Stochastic modeling  
  - Supply chain optimization  
  - Decision support systems

---

## Usage

- Open `FINALEXAMMODELANYLOGIC.alp` in **AnyLogic** to explore and run the simulation.
- Modify parameters and scenarios to test alternative logistics or demand conditions.
- Refer to `Business_Simulation_FinalReport.pdf` for detailed explanations and results.

---

## Author

**Diego Julio Valenzuela Roca**  
MSc in Business Analytics – BI Norwegian Business School  
