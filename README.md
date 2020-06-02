# Smart-Queue-Monitoring-System
This is the Project made for "Intel Edge AI for IOT Developers Nanodegree Scholarship" program. It tests Scenarios across Manufacturing, Retail and Transporation, running the Model Inference on Intel DevCloud using CPU, IGPUs, VPUs and FPGAs for testing.
## Project README

**By** - Abhik Banerjee

**Contact** - abhik@abhikbanerjee.com, abhik.banerjee.1999@gmail.com, abhikb.cse2017@nsec.ac.in

**LinkedIn** - [Abhik Banerjee](https://www.linkedin.com/in/abhik-banerjee-591081164/)

**Programming Language** - Python 3.5

**Framework** - Intel OpenVINO

**Models Used** - [person-detection-retail-0013](https://docs.openvinotoolkit.org/2018_R5/_docs_Retail_object_detection_pedestrian_rmnet_ssd_0013_caffe_desc_person_detection_retail_0013.html)

**Hardwares Used** - 
1. CPU (Intel Core i5 6500TE).
2. Integrated GPU (Intel Core i5 6500TE).
3. VPU (Intel Neural Compute Stick).
4. FPGA (Intel Vision Accelerator Design (HDDL-R)).

[For More](https://devcloud.intel.com/edge/get_started/devcloud/)

### Please go to "Visual Metrics for Hardware Comparisons" for Results

### Project Write-Up - "Choose the Right Hardware. (Writeup).pdf"

## How it Works

The *Create_Job_Submission_Script.ipynb* and *Create_Python_Script.ipynb* files create the necessary artifacts for running the jobs. The following Jupyter Notebooks are used to test the Model Performance on the devices using three different Videos. This inference job takes place on **Edge Nodes** on *Intel DevCloud*.

1. Manufacturing_Scenario.ipynb - Uses the Manufacturing.mp4 file in the **original_videos** directory for running inference jobs.
2. Retail_Scenario.ipynb - Uses the Retail.mp4 file in the **original_videos** directory for running inference jobs.
3. Transportation_Scenario.ipynb - Uses the Transporation.mp4 file in the **original_videos** directory for running inference jobs.

The results for each inference job are obtained from the "output.tgz" file. The "stdout.log" and "stderr.log" files record any output and errors during the whole process respectively.

## Hope you like it! Enjoy.
