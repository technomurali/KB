### Golden Prompt 1: 
### 1\. Problem Definition (Mandatory First Step)

Before any development begins, clearly and explicitly define:

*   **Problem Statement**  
    What exact problem is being addressed?
    
*   **Gap Analysis**  
    What gap or deficiency exists in the current system or workflow that this solution is intended to fill?
    
*   **Purpose**  
    Why is this solution required, and what value does it add?
    
*   **Expected Outcome**  
    What measurable or observable outcome should exist once the solution is implemented?
    

* * *

### 2\. Scenario Identification

List and describe **all relevant scenarios** that must be handled in the implementation, including but not limited to:

*   **Positive Scenarios**  
    Normal and expected user flows that should succeed.
    
*   **Negative Scenarios**  
    Invalid states, incorrect inputs, or disallowed actions that must be handled gracefully.
    
*   **Edge Cases**  
    Boundary conditions, rare states, or unusual combinations that could otherwise cause failure or inconsistency.
    

* * *

### 3\. Clarification Questions (Only When Valuable)

*   Ask clarification questions **only if they add meaningful value** to the correctness or completeness of the implementation.
    
*   Each clarification must be presented as a **multiple-choice question**.
    
*   For every question, include:
    
    *   Clearly labeled options (A, B, C, …)
        
    *   A **recommended option** based on your best judgment
        

**Response format expected from me:**  
`Q1 = A`, `Q2 = C`, etc.

* * *

### 4\. Approval Gate (No Development Before Approval)

*   **Do not start development until explicit approval is received.**
    
*   If I reply with **“approve”** without selecting any options:
    
    *   Proceed using **all of your recommended options** by default.
        

* * *

### 5\. Implementation Planning (After Approval)

Once approval is received:

*   Generate a **clear, step-by-step TODO list** that:
    
    *   Addresses **all identified scenarios** (positive, negative, edge)
        
    *   Is implementation-ready and unambiguous
        

* * *

### 6\. Development Execution

*   Proceed with development strictly according to the approved plan and TODO list.
    
*   Ensure consistency with the defined problem statement, purpose, and expected outcome.
    

* * *

### 7\. Git Commit Message (Mandatory Final Step)

After development is complete, generate a **single Git commit message** that accurately reflects the nature of the change.

Use the following conventions:

*   `fix: <comment>`  
    For bug fixes or corrections to existing behavior
    
*   `NewRequirement: <comment>`  
    For newly introduced functionality or features
    
*   `improvement: <comment>`  
    For enhancements or optimizations to existing functionality
    

You may extend this convention logically if needed, but it must remain consistent with the intent above.