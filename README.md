# intel-oneAPI

#### Team Name - Team NextIn
#### Problem Statement -  Object Detection For Autonomous Vehicles
#### Team Leader Email - hansupadhyay755@gmail.com
Link of the article in Medium : https://medium.com/@hansupadhyay755/safeguarding-autonomy-enhanced-object-detection-for-autonomous-vehicles-with-distance-mapping-and-a0a1f4682199

## A Brief of the Prototype:
  ![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/6b9127fb-1160-4916-9596-c603b143fc9a)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/dcda3486-7f76-4e73-98d7-82fd4b37fede)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/4c949825-6e71-4653-98c8-afd9bcb3f022)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/c0992d3b-275d-4d45-81ba-d1863813ea73)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/060ec4bd-cf52-49c1-8148-f3a6f634b6ce)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/9589fb7b-fac7-4b7b-84f7-0c291c0ce9e6)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/0bc58bb1-0772-43e8-86ec-c32c49549a42)
![image](https://github.com/hansupadhyay007/intel-oneAPI/assets/112337432/650604ee-99ee-4c1a-b31c-3e2b0d409d22)


## Tech Stack: 
   + Intel Extension for PyTorch
   + OpenCV
   + Intel Extension for TensorFlow
   + Intel Distribution for Python
   + Intel Developer Cloud
   + ModelZoo
   
   
## Step-by-Step Code Execution Instructions:
 1. Connect to Intel DevCloud: Use SSH to connect to the Intel DevCloud remote server. Replace <username> and <hostname> with your DevCloud credentials.
 2. Prepare the environment: Set up the required software environment by loading the necessary modules. For YOLO NAS, you may need to load Python, OpenVINO, and     other relevant modules. Check with the DevCloud documentation for the specific commands.
 3. Clone the YOLO NAS repository: Clone the YOLO NAS repository from the source. Use the git clone command to clone the repository.
 4. Navigate to the YOLO NAS directory: Move to the cloned repository's directory.
 5. Install dependencies: Install the required dependencies for YOLO NAS. Typically, these dependencies are specified in a requirements.txt file.
 6. Download the YOLO NAS model weights: Obtain the YOLO NAS model weights either from the repository or other sources. Ensure that you have the correct model    files available locally.
 7. Configure job parameters: Prepare the job submission script. Create a new file, e.g., run.sh, and include the necessary commands to execute the YOLO NAS model. This may involve setting environment variables, specifying the input and output paths, and selecting the device to use (e.g., CPU, GPU, VPU). Consult the YOLO NAS documentation for the required script contents.
 8. Submit the job to the DevCloud: Submit the job to the Intel DevCloud using the qsub command. Pass the path to the run.sh script as an argument.
 9. Retrieve the results: Once the job is completed, you can retrieve the output files generated during inference. These files may include the detection results, logs, and any other relevant outputs. 
  
## What I Learned:
   + We explored a range of Intel's software development tools and libraries, including the AI analytics toolkit and its libraries.
   + Using Intel® AI Analytics Toolkits we were able to enhance performance speed in training data.
   + Brainstormed with novel algorithms for different kinds of object detection specific to autonomous vehicles.
   + Implemented Object detection alongwith distance mapping of nearby objects in order to prevent collisions.
   + We've been able to custom label/annotate the objects in detection.
   + The AI analytics toolkit is a set of libraries and tools that can be used for machine learning and data analytics.
   + By leveraging the AI analytics toolkit and SYCL/DPC++ libraries, developers can write code that is optimized for the Intel hardware platform. This can help to speed up development time, improve performance, and enable developers to tackle more complex problems.
