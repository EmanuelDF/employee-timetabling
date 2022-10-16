# Algorithms for Employee Timetabling Problem (ETP) solution

This is a brute force and an approximate genetic type algorithm, developed during the production of an article as part of the evaluation of the discipline Algorithms and Data Structures - PPCA/UnB.

The problem of the work schedule of socio-educational agents in the Hospitalization Unit in Brazil is reported, in order to adapt and optimize the weekly workload of 40 hours, with lower cost and need for adjustments.

### Rules
- Socio-educational agents work on a 24h x 72h scale (24 hours of work x 72 hours of rest);
- At the end of the monthly cycle, the socio-educator must have completed and equivalent to 40 hours per week;
- Each module must have at least 2 agents per shift;
- At the end of the monthly cycle, the socio-educator must have completed and equivalent to 40 hours per week. Excessive or missing hours are controlled through workload adjustments in the following month;
- Legal leave of absence of civil servants should be considered, examples: vacations, allowances, medical certificates, etc. Absences are of the type: working hours adjustment (ACH), allowance (AB) and Vacation.

### Run
- config the raw_data.yaml
- go to main.py and execute

## References

* Samuel Lukas, Arnold Aribowo and Milyandreana Muchri (2012). [Solving Timetable Problem by GeneticAlgorithm and Heuristic Search Case Study](https://www.intechopen.com/chapters/30303): Universitas Pelita Harapan Timetable, Real-World Applications ofGenetic Algorithms, Dr. Olympia Roeva (Ed.), ISBN: 978-953-51-0146-8, InTech.
* [Genetic Algorithms explaination by Rayen MHAMDI](https://rayenmhamdi.github.io/ai/ga/)
