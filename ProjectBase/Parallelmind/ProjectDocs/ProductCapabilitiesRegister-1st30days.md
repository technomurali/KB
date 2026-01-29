ParallelMind – Current Feature Inventory (Categorical)
======================================================

* * *

1\. Core Architecture & System Foundation (5)
---------------------------------------------

1.  **Root Folder Configuration System**  
    Configure any local folder as the cognitive root.
    
2.  **Index JSON Generation & Management**  
    Automatic creation and maintenance of `*_index.json` capturing structure, relations, and state.
    
3.  **Canvas-Based Visualization Engine**  
    Files, folders, images, and decisions rendered as nodes on a central canvas.
    
4.  **Persistent State Engine**  
    Node position, size, collapse state, lock state persisted across sessions.
    
5.  **Multi-Tab Workspace System**  
    Multiple canvases/files opened simultaneously with independent state.
    

* * *

2\. Node Interaction & Spatial Control (7)
------------------------------------------

6.  **Free Node Dragging & Positioning**  
    Nodes can be moved freely on the canvas.
    
7.  **Node Resizing (Unlimited Scaling)**  
    Nodes can be resized without artificial limits.
    
8.  **Node Minimize / Maximize with Persistence**  
    Compact or expand nodes while retaining state.
    
9.  **Node Lock / Unlock System**  
    Prevent accidental movement or resizing.
    
10.  **Folder Collapse / Expand with Persistent State**  
     Tree nodes can be collapsed or expanded and remembered.
     
11.  **Folder Drag to Move Entire Subtrees**  
     Reparent folders and their children visually and structurally.
     
12.  **Context-Aware Right-Click Menus**  
     Smart enable/disable based on selection and context.
     

* * *

3\. File, Folder & Content Operations (5)
-----------------------------------------

13.  **Create / Rename / Delete for Folders**  
     Full CRUD operations from the UI.
     
14.  **Create / Rename / Delete for File Nodes**  
     File-level CRUD with parity to folder workflows.
     
15.  **Text & Markdown File Editing**  
     Editable content directly within the app.
     
16.  **Live File Content Preview**  
     Read-only previews for text and markdown files.
     
17.  **Auto-Save with State Preservation**  
     Content auto-saves without cursor or focus loss.
     

* * *

4\. SmartPad & Semantic Content (4)
-----------------------------------

18.  **SmartPad Markdown Editor**  
     Dedicated semantic editor for structured thinking.
     
19.  **Edit ↔ Preview Toggle**  
     Seamless switching between markdown source and rendered view.
     
20.  **Purpose / Details Semantic Fields**  
     Structured metadata attached to nodes.
     
21.  **Decision Node Type with If/Else Logic**  
     Logical branching nodes with editable conditions.
     

* * *

5\. Image & Media Handling (5)
------------------------------

22.  **Image Node Type**  
     Images represented as first-class nodes on canvas.
     
23.  **Polaroid-Style Image Rendering**  
     Unified visual treatment for portrait/landscape images.
     
24.  **Full-Image Nodes**  
     Expanded image display mode.
     
25.  **Copy–Paste Images Directly into Canvas**  
     Clipboard image ingestion without file dialogs.
     
26.  **Image Preview in Side Panel**  
     Contextual image inspection when selected.
     

* * *

6\. Navigation, Search & Discovery (3)
--------------------------------------

27.  **Left Panel File & Folder Search**  
     Search across structure with quick selection.
     
28.  **Search-to-Canvas Synchronization**  
     Selecting search results highlights nodes on canvas.
     
29.  **Tree-Based Visibility Integration**  
     Images and files correctly reflected in folder tree hierarchy.
     

* * *

7\. Cognitive Ergonomics & Visual Control (4)
---------------------------------------------

30.  **Configurable Node Font Size**  
     User-controlled readability.
     
31.  **Node Font Color Control (Black / White)**  
     Contrast tuning for cognitive comfort.
     
32.  **Grid View with Adjustable Spacing**  
     Optional spatial alignment aid.
     
33.  **Edge Opacity & Visual Noise Control**  
     Reduce clutter in dense graphs.
     

_(If you want to cap strictly at 30, these last 4 are often grouped as one “Appearance Settings” feature.)_

* * *

Summary (Clean)
---------------

*   **Core system & canvas:** 5
    
*   **Node interaction & spatial control:** 7
    
*   **File & content operations:** 5
    
*   **Semantic thinking tools:** 4
    
*   **Image & media:** 5
    
*   **Navigation & search:** 3
    
*   **Cognitive ergonomics:** 3–4
    

### ✅ **Total: ~30–31 real, user-visible features**


ParallelMind – Chronological Commit History (Cleaned)
=====================================================

### **Foundation Phase**

1.  Initialize React + TypeScript project
    
2.  Add folder and file structure with comments
    
3.  Change `index.html` location
    
4.  Add left sidebar, main canvas area, and right sidebar
    
5.  Implement root folder configuration and JSON generation with node icons
    
6.  Show node details on selection with auto-save and persistence
    
7.  Implement desktop Tauri environment
    
8.  Open folder on double-click for folder nodes
    
9.  Add canvas header with icon-only / title-only / name-only display modes
    
10.  Fix node selection and deselection issues in node details panel
     

* * *

### **Core Canvas & Node System**

11.  Add footer bar and expand side panel maximum width
     
12.  Add global header with settings and theme support
     
13.  Remove all node types except detailed node; add minimize/maximize
     
14.  Rewrite entire index JSON logic for root folder configuration
     
15.  Design folder node SVG style
     
16.  Minor refinements to folder SVG path
     
17.  Remove old handles and add new handles
     
18.  Add node font size setting
     

* * *

### **Interaction Stability & Control**

19.  Fix root node inner content size issues
     
20.  Implement folder node collapse and expand on click
     
21.  Complete basic look and feel for folder and file nodes
     
22.  Fix file and folder node issues
     
23.  Adjust file node sizing
     
24.  Complete node rendering
     
25.  Fix zoom-related issues
     
26.  Add show-all-nodes method with zoom in/out
     
27.  Implement node lock functionality
     
28.  Fix root index logic, zoom fit, icon display, and file node color issues
     
29.  Adjust node spacing
     

* * *

### **Advanced Node Interaction**

30.  Implement multi-tab system
     
31.  Move “Lock Node Position” control to canvas header
     
32.  Persist node position changes
     
33.  Add node minimize and maximize with persistence
     
34.  Allow unlimited node size scaling with 10% steps
     
35.  Reduce size of canvas header context menu
     
36.  Disable folder open on double-click
     
37.  Add open-file action to node context menu
     
38.  Add Decision node type with editable fields and context-menu creation
     
39.  Match decision node stroke thickness to folder node
     

* * *

### **Decision Logic & Context Enhancements**

40.  Add decision details field with if/else text input
     
41.  Truncate folder and file purpose display to 250 characters
     
42.  Update zoom-view icon and tooltip to “Show Details”
     
43.  Add fixed-size decision node handles at SVG vertices
     
44.  Improve context menu auto-close with dual event listeners
     

* * *

### **File, Image & Media Capabilities**

45.  Enable folder creation from frontend
     
46.  Implement file delete and rename functionality
     
47.  Add file content preview for text and markdown nodes
     
48.  Make SmartPad fill remaining panel height
     
49.  Add SmartPad picklist dropdown and editable content area
     
50.  Add SmartPad preview icon
     
51.  Add desktop and browser modes with F11 fullscreen toggle and app mode indicator
     
52.  Add Image node type and canvas menu entry
     
53.  Enable copy–paste of images into canvas
     
54.  Rename ImageNode to PortraitImage across node types and menus
     
55.  Remove legacy portrait/landscape image nodes and map to polaroid rendering
     
56.  Add node resizer
     
57.  Display image nodes correctly in folder tree
     
58.  Add animated parent–child paths
     
59.  Update edge endings with arrow triangle symbols
     
60.  Add folder-like create/rename/delete workflow for file nodes
     
61.  Add image create, update, delete, and rename operations
     

* * *

### **Content Editing & Usability**

62.  Preserve cursor position and focus after SmartPad auto-save
     
63.  Add image preview in right panel on image node selection
     
64.  Add rich paste support in SmartPad (HTML → Markdown)
     
65.  Preserve pasted markdown spacing in SmartPad
     
66.  Auto-resize purpose and details fields when expanded
     
67.  Rename “Zoom View” to “Show Details”
     

* * *

### **Appearance, Layout & Navigation**

68.  Refactor appearance settings into accessible accordion sections
     
69.  Add edge opacity control in settings
     
70.  Add grid view with configurable horizontal and vertical spacing
     
71.  Add left panel file and folder search with recent chips and canvas sync
     
72.  Remove placeholder text from left and right panels
     

* * *

### **Tree & Image System Refinement**

73.  Fix node lock issues
     
74.  Add folder drag toggle to move child subtrees
     
75.  Add persistent folder tree collapse/expand toggle
     
76.  Fix tree open/close logic using `isTreeCollapsed` from JSON
     
77.  Add full-image node support
     
78.  Set full-image nodes as default image nodes
     

* * *

### **Latest Enhancements**

79.  Add black/white node font color setting and apply to canvas nodes


SECTION 1 — Reality Creation (Do this ONCE)
-------------------------------------------

**Objective:** Make the idea exist in a usable form.

### 1.1 Existence Check

*    Can I interact with it end-to-end?
    
*    Does it have a visible form (UI / prototype / physical object)?
    
*    Does it produce _any_ output?
    
*    Can I repeat the interaction?
    

> If any answer is “No” → stop. Build only that.


