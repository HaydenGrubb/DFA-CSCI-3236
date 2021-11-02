# DFA-CSCI-3236
Deterministic Finite Automata

{0,1}		accepted language - strings consists of this language will be accepted
{a,b,c,d}	set of states - all the states that the DFA traverses through
{a}			start state - beginning state of the DFA
{d}			accept state - set of states that will be accepted in DFA

transition functions - by inserting characters from the language 
the next state that would be reached is recorded
{a,0}->b	
{a,1}->a	
{b,0}->c	
{b,1}->a		
{c,0}->c	
{c,1}->d	
{d,0}->d	
{d,1}->d
