**Optimizing Job Shop Scheduling in a Manufacturing Plant using Genetic Algorithm**

**Overview:**
This project aims to tackle the complex problem of job shop scheduling in a manufacturing plant by utilizing a genetic algorithm.
The objective is to develop an efficient system that determines the optimal sequence and timing of operations for multiple jobs across several machines,
minimizing the overall production time and maximizing throughput.

**Problem Statement:**
In a manufacturing environment with various machines (e.g., cutting machines, drilling machines, assembly stations), 
each product requires a specific sequence of operations on these machines.
 The challenge is to find the best schedule that considers machine capacities and job dependencies.

**Example Input:**
A job is defined as a sequence of operations, where each operation is specified by a machine and its required processing time. For example:

  * Job 1: M1[10] -> M2[5] -> M4[12]
  * Job 2: M2[7] -> M3[15] -> M1[8]
    
Here, Job 1 starts on machine M1 and takes 10 time units, then moves to M2 for 5 time units, and finally to M4 for 12 time units. Job 2 follows a different sequence.


**Key Features**
  * Input Flexibility: The system allows users to specify the number of machines and input the job sequences, with each job having its own sequence of operations and processing times.
  * Output Visualization: The system generates a detailed schedule for each machine, showing the start and end times for each job's operation. The results can be visualized using a Gantt chart.

**Implementation Details**
The project involves:

  * Chromosome Representation: Encoding the job sequences for the genetic algorithm.
  * Genetic Operations: Implementing cross-over and mutation functions to evolve the population towards an optimal solution.
  * Objective Function: Defining a function to evaluate the fitness of each solution, aiming to minimize the overall production time or maximize throughput.


**Deliverables**
  * Source Code: Fully implemented system in your preferred programming language.
  * Report: A concise PDF report (up to 3 pages) detailing the problem formulation, including the chromosome representation, cross-over, mutation, and the objective function used. The report should also include test cases.
  * Demo: A live demonstration of the system, where you may be asked to explain the code and make minor modifications.
