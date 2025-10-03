# Travel Itinerary Optimization Using Genetic Algorithm
## Description:

This project utilizes Genetic Algorithm (GA) to optimize travel itineraries for tourists. Given a set of attractions, their ratings, durations, and travel times, the system generates the most efficient travel plan while minimizing cost and time. The optimization focuses on balancing the total enjoyment, travel time, and cost, while adhering to user-defined constraints like maximum hours per day.

## Features:

Attraction Management: The system includes information about attractions, including name, duration, rating, and cost.

Genetic Algorithm: Uses GA for optimization, where solutions (itineraries) evolve through crossover, mutation, and elitism.

Penalty Handling: Implements penalties for constraints like exceeding daily time limits or visiting duplicate attractions.

Itinerary Display: Outputs the optimized itinerary, including arrival/departure times, duration, and costs for each attraction.

## Key Components:

Genetic Algorithm:

Population Initialization: Generates an initial population of random itineraries.

Selection: Chooses the best individuals (itineraries) based on fitness (i.e., enjoyment score minus penalties).

Crossover & Mutation: Evolves new itineraries through crossover and mutation operations.

Elitism: Ensures the best itineraries from each generation are carried over to the next generation.

Itinerary Calculation:

Calculates daily durations, enjoyment scores, total costs, and ensures no attraction is repeated.

Considers travel time between attractions and enforces daily time limits.

## Output:

Displays the optimized itinerary with attraction details like name, rating, duration, cost, and travel time between attractions.

Provides a final report of the total enjoyment, cost, and time.
