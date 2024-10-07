```mermaid
flowchart TD
 Start([Generate Random Number]) --> A(Read Input)
 A -->|Invalid Input| B[Response-Error]
 A -->|Valid Input| C{Check Number}
 C -->|Input is Too High| E(Response-Too High:Try Again)
 C -->|Input is Too Low| F(Response-Too Low:Try Again)
 C -->|Correct Input| End([Response-Correct!])
 ```
