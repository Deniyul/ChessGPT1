# ChessGPT1
Autonomous Chess Engine
```mermaid
sequenceDiagram
    autonumber 
    actor Host as Host/GUI(Arena)
    participant Engine as Engine
    participant Parser as UCI Parser
    participant Position as Position (Board/FEN)
    participant MoveGen as MoveGenerator (pseudoLegalMoves etc.)
    participant Rule as RuleChecker (isSquareAttacked/ inCheck)
    participant MoveObj as Move (Move.fromUci/ to Uci)



```mermaid

