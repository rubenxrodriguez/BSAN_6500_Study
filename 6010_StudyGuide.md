Final Study Guide (Conceptual)
Operations Management – BSAN 6010

(Comprehensive conceptual guide integrating lectures, slides, and previous project chats)

1. Time Series Forecasting (Conceptual)

Goal: Understand patterns in data (trend, seasonality, randomness) and select the forecasting model most appropriate to the observed behavior.

1.1 Purpose of Forecasting

Forecasting supports decisions in:

Process design, capacity planning, aggregate planning, scheduling, inventory management (see forecasting table on page 1 of TSforecast.pdf ).

1.2 Forecasting Process

As shown in the Forecasting Process diagram (pages 2–3, BSAN6010_IntroTimeSeriesForecasting.pdf ):

Identify purpose

Collect historical data

Plot & diagnose patterns

Select an appropriate model

Fit the model

Evaluate accuracy (MAD, MAPE, RMSE)

Decide if accuracy acceptable

Adjust model or parameters

Forecast forward

Monitor & update

1.3 Identifying Demand Behavior

From page 9 of forecasting slides:

Trend – long-term increase/decrease

Cycles – long multi-year fluctuations

Seasonality – repeating predictable calendar pattern

Random variation – noise with no pattern

1.4 Comparisons of Models & When to Use Them

(From TSforecast.pdf, pages 2–8 & 13–21 )

Model	Use When	Pros	Cons
Naïve	Data random or stable	Simple benchmark	Very inaccurate for trend/seasonality
Moving Average (k-period)	Short-term smoothing; weak trend; stable seasonality	Smooths noise	Lags trend; need to choose k manually
Exponential Smoothing (α)	No trend, no seasonality	Lightweight, adaptive	Cannot capture trend/seasonality
Trend Projection (Linear Regression)	Strong linear trend	Forecasts trend well	Sensitive to turning points, assumes linearity
Classical Decomposition	Both trend & seasonality present	Handles full behavior; used in LawnKing project	Requires long data; more complex
1.5 Measures of Accuracy

(From pages 5–7 of TSforecast.pdf )

MAD: average absolute error

MAPE: error as % of actual

Bias: cumulative error (systematically high/low)

RMSE: penalizes large errors

1.6 Key Concepts for Exam

Interpret patterns and match to model

Compare model performance conceptually

Explain why last year’s forecast accuracy affects next year’s projections

Recognize overfitting (model fits old data too well, performs poorly for new data)

2. Process Flow Analysis (Conceptual)

Relies heavily on Process Selection.pdf

2.1 Understanding the Current Process

Key definitions:

Capacity: maximum rate of output of a process step

Cycle Time: average time between unit completions

Throughput Time: time for a unit to pass entire system

Bottleneck: step with the lowest capacity → constrains entire process

Throughput Ratio: (Total processing time) ÷ (Total throughput time) (from page 10)

2.2 What the Exam Will Ask

Identify bottleneck from a diagram

Calculate capacity of each step

Explain why throughput time ≠ cycle time

Recommend improvements (add labor, reorganize flow, reduce setup time)

2.3 Process Improvement (Class Exercise 4)

General improvements include:

Balancing workload across stations

Reducing variability or setup time

Resequencing tasks

Adding parallel resources

Moving from batch → flow where possible

2.4 Production Types & Relevance

(From pages 6–13 of Process Selection.pdf)

Continuous – high volume, low variety

Assembly Line – standardized products (cars)

Batch – moderate volume/variety

Job Shop – customized, low volume

Project – one-of-a-kind, long duration

Understanding these helps diagnose fit between process & strategy.

3. Quality Management (Conceptual)

Slides from Quality Mgmt.pdf pages 1–16

3.1 Quality of Design vs. Quality of Conformance

Quality of Design: how well product is designed to meet customer needs

Quality of Conformance: how well the production process meets the design specifications

Mayo Clinic Standardization Example:

Standardized checklists, workflows, handoffs—reducing variation and aligning practice across physicians → high conformance.

3.2 Poka-Yokes (Mistake-Proofing)

Examples (based on Lean slides & class discussion):

Shapes/slots that only fit one direction

Car won’t shift out of park unless brake pressed

Color-coded medication caps

Hospital barcodes for patient ID (Mayo Clinic example)

3.3 Costs of Quality

(from page 8 Quality Mgmt.pdf)

Prevention – training, design reviews, mistake-proofing

Appraisal – inspection, audits

Internal Failure – scrap, rework

External Failure – warranty, recalls, lawsuits

3.4 Tools for Continuous Improvement (7 QC Tools)

(from page 16)

Flowcharts

Check sheets

Histograms

Pareto charts

Cause-and-effect (fishbone) diagrams

Scatter plots

Control charts

These tools help identify root causes and prioritize improvements.

3.5 Class Exercise 6

Focus on applying:

Identifying defect source

Determining whether design or conformance issue

Selecting appropriate quality tool to diagnose system

4. Supply Chain Management (Conceptual)

Material integrated from:

Supply Chain Mgmt.pdf pages 1–29

Previous chat’s Ch.16 & 17 study guide

Polaris Case (LP model for transportation)

4.1 What SCM Covers

(Slide: page 3)

Production planning

Supplier selection

Materials purchasing

Facility location

Distribution

Inventory control

4.2 Efficient vs. Responsive Supply Chains

(See table on page 9)

Efficient	Responsive
Predictable demand	Unpredictable demand
Low-cost focus	Speed / flexibility
High utilization	Extra capacity
Minimize inventory	Hold safety stock
Supplier chosen on cost	Supplier chosen for speed/flexibility
4.3 Transportation LP Model (Polaris Case)

(Your previous chat referenced Exhibit 4 & class exercise 7)

Conceptual things to know:

Objective: minimize total shipping cost

Balanced vs. unbalanced models (pages 28–29)

How to evaluate adding a new facility / plant

What qualitative factors matter (labor market, tariffs, supplier maturity, political risk)

4.4 Bullwhip Effect

(Strong visuals on pages 13–15)

Key Drivers:

Order batching

Price fluctuations

Demand signal distortion

Lack of information sharing

Ways to reduce:

Share real-time POS data

Reduce lead time

Stabilize pricing (EDLP)

Vendor-managed inventory (VMI)

4.5 Sourcing (Chapter 17 Concepts)

(From pages 17–21)

Goals: access technology, reduce costs, minimize risk, maintain ethics

Supplier selection considerations: reliability, location, quality systems

Supply base optimization → avoid too many or too few suppliers

5. Lean Tenets & Production (Conceptual)

Slides from Lean Production and Tenets.pdf pages 1–16

5.1 JIT / Lean Core Philosophy

Produce only what is needed when it is needed

Remove all waste (“muda”)

Continuously improve processes

Emphasis on flow, not efficiency in isolation

5.2 Seven Forms of Waste

(page 4)

Overproduction

Waiting

Transportation

Excess processing

Too much inventory

Unnecessary motion

Defects

5.3 Why Large Inventory Hides Problems

(page 6)

Inventory covers up:

Poor quality

Machine issues

Unreliable suppliers

Inefficient layouts

Lengthy setups

Lowering inventory exposes bottlenecks → improves system design.

5.4 Pull System & Kanbans

(page 9–11)

Downstream step signals upstream when more materials are needed

Prevents overproduction

Requires reliable suppliers & stable processes

5.5 Types of Inventory to Know

(From Inventory Overview.pdf page 4 )

Raw Materials

WIP

Finished Goods

Safety Stock / Cycle stock / Pipeline stock

5.6 JIT Benefits & Challenges

Benefits: low inventory, shorter lead time, faster detection of problems

Challenges: supply chain disruptions, global suppliers, variability, labor constraints

5.7 Class Exercise 5

Topics include:

Identifying forms of waste

Designing a kanban

Evaluating process flow inefficiencies

6. Summary of Major Case Examples You Should Know
LawnKing Forecasting (From Previous Chat)

Classical decomposition used to separate seasonal + trend components

Matching forecast model to observed data

Using MAD / MAPE to compare alternative models

Discuss limitations with forecasting future years

Polaris LP Case (From Previous Chat)

Determining optimal shipping plan from Roseau/Spirit Lake vs. hypothetical China facility

Integrating transportation cost + production cost

Discussing qualitative considerations (risk, tariffs, shelf-life, supplier maturity)

Mayo Clinic Standardization

Standard work protocols

Reduces variance, improves conformance quality

Supported by poka-yokes and checklists

Technical Study Guide – What to Include (Separate Document)

You asked for a note summarizing what belongs in a technical (Excel/Python/Solver) guide. Add the following:

Time Series Forecasting – Technical

Implementing classical decomposition (LawnKing)

Excel formulas for MA, ES, trend projection, seasonal indices

Accuracy calculation examples: MAD, MAPE

Regression in Excel (Data Analysis → Regression)

Linear Programming (Polaris & Transportation Model) – Technical

Setting up Solver: objective cell, changing cells, constraints

Transportation tableau construction

Balanced vs. unbalanced model constraints

Sensitivity report basics

Process Flow – Technical

Numerical examples of capacity, cycle time, throughput

Calculating resource utilization

Quality – Technical

Building and interpreting control charts

Computing process capability (Cp, Cpk if shown in class)

Lean – Technical

Kanban formula (if covered)

Takt time calculations

In Lectures but NOT Included in This Conceptual Study Guide

Topics covered in lecture slides but intentionally excluded from conceptual guide (you may want to review but they are more technical):

MRP Matrix construction (Inventory slides pages 20–22)

Detailed EOQ calculations

ABC Analysis computations

Full MRP explosion tree + BoM structure math

LP Solver error messages and troubleshooting (pages 7–14 of LP slides )

Inventory reorder-point formulas (safety stock math)

Detailed regression output interpretation (coefficients, p-values, R²)

Specific numerical throughput ratio examples

These belong in the Technical Study Guide, not the conceptual one.


