When to use deep agents
-----------------------

Use deep agents when you need agents that can:

*   **Handle complex, multi-step tasks** that require planning and decomposition
    
*   **Manage large amounts of context** through file system tools
    
*   **Delegate work to specialized subagents** for context isolation
    
*   **Persist memory** across conversations and threads

To explain how a **DeepAgent** works using your Switzerland trip request as a case study, we can look at its architecture as a "Digital Project Manager."

Unlike a standard AI that just gives you a quick answer, a DeepAgent uses a structured loop of **Planning**, **Delegation**, and **Storage** to handle complex, multi-step requests like a 300,000 INR budget trip.

* * *

1\. The Core Approach: How DeepAgent Works
------------------------------------------

A DeepAgent doesn't just "guess." It operates in a cycle: **Plan → Act → Observe → Refine**.

### ⚙️ The Four Pillars

| **Component** | **Function in the Architecture** |
| --- | --- |
| **System Prompt** | The "Persona & Rules." It defines the agent’s expertise and constraints. |
| **Planning Tools** | The "Roadmap." A specialized tool (like a `todo_list`) where the agent writes and updates its strategy. |
| **Subagents** | The "Specialists." Smaller, focused agents created to handle specific deep dives (e.g., a "Flight Expert"). |
| **File System** | The "External Memory." A virtual workspace to save research, draft itineraries, and store budget tables. |

* * *

2\. DeepAgent Execution: Switzerland Trip Example
-------------------------------------------------

Here is how the DeepAgent would process your prompt: **"Plan a Switzerland trip within 300,000 INR."**

### Step 1: The System Prompt (The Persona)

The agent is initialized with a prompt like:

> _"You are a Senior Travel Strategist. You must stay under the 300,000 INR limit. Use the `todo_write` tool to plan. Delegate flight searches to the `FlightsSubagent`. Save all budget calculations in `budget.md`."_

### Step 2: Planning Tools (The Strategy)

The agent calls its **Planning Tool** to create a TODO list in its memory:

1.  Research flight costs from India to Zurich (Target: < 70k INR).
    
2.  Calculate cost of 8-day Swiss Travel Pass (~35k INR).
    
3.  Search for budget accommodations in Lucerne and Interlaken.
    
4.  Delegate a subagent to find "Value for Money" dining options (Coop/Migros).
    
5.  Compile final itinerary and check if total $\\le$ 300,000 INR.
    

### Step 3: Subagents (The Specialists)

The main agent "spawns" a **Subagent** for the complex research:

*   **Subagent A (Researcher):** Searches for current flight prices for your specific dates.
    
*   **Subagent B (Finance):** Takes the prices and performs currency conversion (CHF to INR) to ensure the 300k limit isn't breached.
    

### Step 4: File System (The Memory)

As the agent works, it writes to files so it doesn't "forget" details:

*   **`itinerary.txt`**: Drafts the day-by-day plan.
    
*   **`ledger.csv`**: A table of costs.
    
    *   _Flights:_ 75,000 INR
        
    *   _Hotels (7 nights):_ 1,10,000 INR
        
    *   _Passes:_ 40,000 INR
        
    *   _Food/Misc:_ 50,000 INR
        
    *   **Total:** 2,75,000 INR (Safe!)
        

* * *

3\. The Result: Your Switzerland Trip Strategy
----------------------------------------------

Based on this DeepAgent logic, here is a feasible plan for your **300,000 INR** budget:

*   **Duration:** 7–9 Days (The "Sweet Spot" for this budget).
    
*   **Flights:** Aim for **70,000 – 85,000 INR** (Book 3-4 months in advance).
    
*   **Transport:** **35,000 INR** for an 8-day Swiss Travel Pass (covers all trains, buses, and most museums).
    
*   **Accommodation:** **1,10,000 INR** (Average 13k–15k per night). Stay in "base" towns like **Lucerne** or **Interlaken** rather than expensive mountain peaks.
    
*   **Daily Expenses:** **60,000 INR** for food and mountain excursions (e.g., Mt. Titlis or Jungfraujoch).
    
    *   _Tip:_ Use supermarkets like **Coop or Migros** for lunches to save ~15,000 INR.
        

**Would you like me to generate a detailed day-by-day itinerary and save it to a formatted table for you?**