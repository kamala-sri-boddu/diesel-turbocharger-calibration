Calibration and Integration of a Turbocharger for a Single-Cylinder Diesel Engine 🔧

Bachelor's Dissertation Project — Department of Mechanical Engineering, Gayatri Vidya Parishad College of Engineering (Autonomous), April 2024

> This was a team project (4 members). My name is listed below; this repo documents the shared work, not a solo build.

Team: Kuracha Meghana · **Boddu Kamala Sri** · Allada Tejaswini · Bhukya Satwik Naik
Guide: Dr. B. Govinda Rao, Professor & HOD, Mechanical Engineering

Abstract

Turbochargers are widely used in multi-cylinder diesel engines, where overlapping suction strokes give a continuous flow of intake air. A single-cylinder engine has only one suction stroke every two revolutions, so airflow to the turbocharger is pulsating rather than continuous — making turbocharging far harder to implement than on a multi-cylinder engine.

This project incorporates a turbocharger into a single-cylinder diesel engine by adding an **air capacitor** (sized at ~4–5× engine capacity, determined experimentally — this build used 81×) before the intake manifold, to smooth the pulsating flow and maintain turbo boost pressure with minimal turbo lag. The turbocharger was then calibrated and integrated with the engine, and its effect on performance and emissions was measured across different inlet pressures, temperatures and loads.

 What Was Measured

- Performance:** Brake Thermal Efficiency (BTH), Brake Specific Fuel Consumption (BSFC)
- Emissions:** CO, HC, NOₓ, and smoke
- Combustion behavior:** cylinder pressure, net heat release, rate of pressure rise, and mass fraction of fuel burned — all plotted against crank angle, with and without the turbocharger

Experimental Setup

- Engine: Single-cylinder, 4-stroke, water-cooled, multi-fuel VCR research engine (661 cc, 3.5 kW @ 1500 rpm), coupled to an eddy-current dynamometer, with a full sensor/DAQ stack (piezo combustion pressure sensor, crank-angle sensor, NI USB-6210 16-bit DAQ) for real-time pressure–crank-angle logging via "IC Engine Soft" software.
- Turbocharger rig: A 1 HP turbine blower driven through a variable-frequency drive, feeding the intake manifold through an air-heating system, digital manometer, and flow-control valves — allowing inlet air temperature and pressure to be controlled and measured independently.
- Calibration method: The turbocharger's discharge and heat input were each calibrated separately by varying blower frequency/heat input, measuring airflow and outlet temperature at each point, and fitting the relationship with **regression analysis** before the turbocharger was connected to the engine.

Methodology (Summary)

1. Size and validate the air capacitor against engine displacement.
2. Verify engine configuration — connections, leak-free operation.
3. Assemble and configure the turbocharger rig.
4. Calibrate turbocharger discharge (airflow vs. blower frequency, via regression).
5. Calibrate turbocharger heat input (output air temperature vs. heat input, via regression).
6. Connect the turbocharger outlet to the engine intake manifold.
7. Run performance tests at multiple loads, with and without the turbocharger.
8. Compare BTH, BSFC, and emissions (CO, HC, NOₓ, smoke) between the two configurations.

My Role

I contributed to the experimental testing and data analysis — running engine performance tests at varying loads, recording manometer/airflow/temperature readings, and working through the regression-based calibration of the turbocharger's discharge and heat input.

Skills Demonstrated

- Experimental testing and instrumentation (pressure, temperature, airflow, crank-angle sensors; DAQ-based data logging)
- Sensor/system calibration using regression analysis
- IC engine performance evaluation (BTH, BSFC, volumetric & mechanical efficiency)
- Emissions analysis (CO, HC, NOₓ, smoke)
- Technical report writing and data interpretation

 File

- [`project_report.docx`](./project_report.docx) — full dissertation report

---
Boddu Kamala Sri — [LinkedIn](https://linkedin.com/in/kamala-sri-boddu-57507a20b)

