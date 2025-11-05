# Welcome 

<img width="860" height="368" alt="image" src="https://github.com/user-attachments/assets/9810ee62-d8ad-47ee-a73f-b10dec1fe9ed" />

You made it to the Jupyter Hub for the MOPITAS Autumn School 2025. 

Later, you will find Jupyter Notebooks here that we will use during hands-on sessions.

If you choose to work on your own laptop during the hands-on sessions, please follow these steps to prepare for the hands-on sessions: 

1. Clone the repository: ```https://github.com/daisybio/MOPITAS_Autumn_School.git```
   
2. Pull the docker image:
    ```bash
    # 0. Start docker on your machine 
    
    # 1. Pull the pre-built image 
    docker pull ghcr.io/daisybio/mopitas_autumn_school/student-notebook:latest 
    
    # 2. Run the container (Jupyter will be on http://localhost:8888) 
    docker run -it -p 8888:8888 ghcr.io/daisybio/mopitas_autumn_school/student-notebook:latest
    ```

3. Download the datasets archive: [https://gigamove.rwth-aachen.de/de/download/5dcc3471b818d3a169ee259afd428081](https://gigamove.rwth-aachen.de/de/download/8a6d885a10224997f58459ad3ef4f1bf). A password was sent to you via email.
   Please note that it has ~17GB so plan accordingly!

5. Unzip the datasets: ```tar -xzf datasets.tar.gz```

6. Check the folder structure. It should look like this:
   That's a great way to visualize a directory structure\! Here is the graph, formatted like the output of the Unix `tree` command:
    ```
    .
    ├── datasets
    │   ├── Hands_on_1_Spatial_Data
    │   ├── Hands_on_2_LIANA_MistY
    │   ├── Hands_on_3_NiCo
    │   ├── Hands_on_4_Tangram
    │   └── Hands_on_5_Spapros
    └── work
        └── example.ipynb
    ```

Looking forward to seeing you soon!
