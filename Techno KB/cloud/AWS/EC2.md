EC2 sizing & configuration options
----------------------------------
We can configure size and configuration of EC2 instance.
*   **Operating System (OS):** Linux, Windows or Mac OS
    
*   **How much compute power & cores (CPU)**
    
*   **How much random-access memory (RAM)**
    
*   **How much storage space:**
    
    *   Network-attached (EBS & EFS)
        
    *   hardware (EC2 Instance Store)
        
*   **Network card:** speed of the card, Public IP address
    
*   **Firewall rules:** security group


*   **Bootstrap** script (configure at first launch): EC2 User Data

    Bootstrapping means launching commands when a machine starts, this   scripts runs only once at the fist instance start first time. 
    Installing updates
    Installing software's
    Downloading common files from the internet.