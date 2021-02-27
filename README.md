# N-soft-sets
Diving Championships Dataset for OWA Aggregation Operators and Multi-agent Decisions with N-Soft Sets.

In competitive diving, the scoring system of individual events works as follows~\cite{Realbuzz}.
There are $k=7$ judges that award points from $0$ (completely fail) to $10$.
Judges score in whole or half points thus $G=\{0, 0.5, 1, 1.5, \ldots , 9.5, 10\}$, that we can for simplicity transform into $G=\{0, 1, 2, \ldots , 19, 20\}$ (we just divide by $0.5$ each score). Thus $N=21$ which means a fine grading.
The judges score a dive based on four elements, namely, approach to the dive, take-off from the platform or springboard, execution (flight through the air) and entry into water. Each diver performs a fixed number of dives.

At the 2019 USA Diving Senior National Diving Championships held from  May 19, 2019 to May 26, 2019,
$p=12$ divers performed $q=6$ dives at the final of the Senior Men Platform competition~\cite{TeamUSA}.
