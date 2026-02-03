NFA to DFA Converter

📌 Project Description:
This tool implements the Subset Construction Algorithm to transform a Non-Deterministic Finite Automaton (NFA) into its equivalent Deterministic Finite Automaton (DFA). In compiler design, this is essential for creating efficient lexical analyzers that do not require backtracking.

⚙️ Key Algorithms:
Epsilon Closure (epsilon-closure): For every state set, we calculate all possible states reachable via epsilon transitions.
Subset Mapping: Each unique set of NFA states is mapped to a single, distinct DFA state.
Final State Identification: If any NFA state within a DFA subset is an accepting state, the entire DFA state is marked as accepting.

🚀 Usage:
Define your NFA: Edit the nfa_trans dictionary where keys are (state, input_symbol) and values are lists of destination states.

Run the script:
python script.py
