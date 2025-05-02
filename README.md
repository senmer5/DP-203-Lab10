# DP-203-Lab10

🧪 **Use an Apache Spark Notebook in a Pipeline**

### 🔍 Why are we doing this lab?
In modern data ecosystems, automation and orchestration play a crucial role in building scalable and maintainable workflows. This lab is designed to demonstrate how Apache Spark notebooks can be seamlessly integrated into Azure Synapse Pipelines, enabling data engineers and analysts to streamline complex processing tasks, ensure reproducibility, and simplify management of data-driven operations.

### 📌 Objective
- Understand how to execute Apache Spark notebooks as part of Synapse Pipelines  
- Learn to build automated, repeatable workflows for data transformation and analysis  
- Discover how to integrate notebooks into production-ready data pipelines with scheduling and monitoring features  

### 🛠️ Prerequisites
Before you begin, make sure you have:
- An active Azure subscription  
- An Azure Synapse Analytics workspace set up  
- A pre-created or existing Spark notebook containing transformation or analysis logic  
- Required permissions to create and manage pipelines in Synapse  

### 📋 Step-by-Step Guide
1. **Prepare Your Spark Notebook**
   - Launch Azure Synapse Studio and navigate to the Develop hub.  
   - Create a new notebook or select an existing one.  
   - Add relevant code blocks for reading data, applying transformations, or visualizing results.  
   - Save your notebook and verify it runs successfully using a Spark pool.  

2. **Create a New Pipeline**
   - Go to the Integrate hub.  
   - Click `+ > Pipeline` to create a new pipeline canvas for your workflow.  

3. **Add a Notebook Activity**
   - Drag and drop the Notebook activity onto the canvas.  
   - Configure the activity settings:  
     - **Notebook**: Choose the notebook you prepared  
     - **Spark pool**: Select the Spark pool for execution  
     - Add parameters if your notebook expects inputs  

4. **Save and Publish the Pipeline**
   - Click **Save** to persist your pipeline.  
   - Then click **Publish All** to deploy your changes to the workspace.  

5. **Trigger and Monitor the Pipeline**
   - Run the pipeline manually or configure a time-based trigger for automated execution.  
   - Monitor the run from the Monitor hub to ensure successful completion and analyze the output logs.  

### ✅ Expected Results
- The selected Apache Spark notebook runs successfully within the Synapse pipeline  
- All transformations or data tasks in the notebook complete without errors  
- Monitoring tools reflect a successful execution, including logs and runtime metrics  

### 📸 Screenshots
_(Include visuals of the notebook activity, pipeline structure, and execution results)_


<img width="1127" alt="1" src="https://github.com/user-attachments/assets/a81bf62f-dccd-4de0-8fd1-c9bc378a12d4" />

<img width="989" alt="2" src="https://github.com/user-attachments/assets/375a4105-dcc8-4587-ada2-e6ed77bf508a" />

<img width="992" alt="3" src="https://github.com/user-attachments/assets/948de07f-56ae-4c19-9fb9-88b9d0269cca" />

<img width="997" alt="4" src="https://github.com/user-attachments/assets/407d1b3e-89fb-4d5b-9fbd-9aa8e74e2f23" />

<img width="1004" alt="5" src="https://github.com/user-attachments/assets/d9d97bfe-eaf7-40fc-b461-3ae28fbb8579" />

<img width="1007" alt="6" src="https://github.com/user-attachments/assets/1dedc6c2-4d95-4744-aa14-4ef638e0c338" />

<img width="1008" alt="7" src="https://github.com/user-attachments/assets/f583a04e-d73b-4af3-a867-c1a71a4377cc" />

<img width="1000" alt="8" src="https://github.com/user-attachments/assets/289ab1e2-b2a3-428a-a739-97c57c88b760" />




