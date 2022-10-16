# Algorithms for Employee Timetabling Problem (ETP) solution

This is a brute force and an approximate genetic type algorithm, developed during the production of an article as part of the evaluation of the discipline Algorithms and Data Structures.</br>
**Applied Computing Graduate Program (PPCA) - University of Brasilia (UnB).**

The problem of the work schedule of socio-educational agents in the Hospitalization Unit in Brazil is reported, in order to adapt and optimize the weekly workload of 40 hours, with lower cost and need for adjustments.

### Rules
- Socio-educational agents work on a 24h x 72h scale (24 hours of work x 72 hours of rest);
- At the end of the monthly cycle, the socio-educator must have completed and equivalent to 40 hours per week;
- Each module must have at least 2 agents per shift;
- At the end of the monthly cycle, the socio-educator must have completed and equivalent to 40 hours per week. Excessive or missing hours are controlled through workload adjustments in the following month;
- Legal leave of absence of civil servants should be considered, examples: vacations, allowances, medical certificates, etc. Absences are of the type: working hours adjustment (ACH), allowance (AB) and Vacation.

### Run
- Config raw_data.yaml
- Execute main.py

## References

1. Samuel Lukas, Arnold Aribowo and Milyandreana Muchri (2012). [Solving Timetable Problem by GeneticAlgorithm and Heuristic Search Case Study](https://www.intechopen.com/chapters/30303): Universitas Pelita Harapan Timetable, Real-World Applications ofGenetic Algorithms, Dr. Olympia Roeva (Ed.), ISBN: 978-953-51-0146-8, InTech.
2. [Genetic Algorithms explaination by Rayen MHAMDI](https://rayenmhamdi.github.io/ai/ga/)
3. Amnon Meisels and Andrea Schaerf. Modelling and solving employee timetabling problems. Annals of Mathematics and Artificial Intelligence,
39(1):41–59, 2003.
4. Christian Artigues, Michel Gendreau, Louis-Martin Rousseau, and
Adrien Vergnaud. Solving an integrated employee timetabling and job- shop scheduling problem via hybrid branch-and-bound. Computers & Operations Research, 36(8):2330–2340, 2009.
5. Mohamed Frihat, Atidel B Hadj-Alouane, and Che ́rif Sadfi. Optimiza- tion of the integrated problem of employee timetabling and job shop scheduling. Computers & Operations Research, 137:105332, 2022.
6. AI Diveev and OV Bobr. Variational genetic algorithm for np-hard scheduling problem solution. Procedia Computer Science, 103:52–58, 2017.
7. Mohammad Nematpour, Habib Izadkhah, and Farnaz Mahan. Enhanced genetic algorithm with some heuristic principles for task graph schedu- ling. The Journal of Supercomputing, pages 1–30, 2022.
8. Thomas H Cormen, Charles E Leiserson, Ronald L Rivest, and Clifford Stein. Introduction to algorithms. MIT press, 2022.