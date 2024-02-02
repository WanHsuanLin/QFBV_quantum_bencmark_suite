"card_to_CNF": instances includes CNF derived from a cardinality constraint. Used in SWAP count optimization. More important than "depth only".
"depth only": instances without CNF.

File name "p{x}_q{y}_d{z}_s{w}.txt" means that the instances in generated for compiling a QAOA circuit with y qubits on a grid coupling graph with x physical qubits. The depth used to generated formulation is z. For z<10, transition-based model is used. Thus, the model is much simpler than the original one. SWAP count limit is w. If w=-1, we don't optmizie for SWAP.
