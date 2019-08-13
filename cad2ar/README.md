# CAD to AR Portal
2019 Conestoga Capstone Project "CAD to AR Portal"

***

## 0. Award
<!---<img src="./images/award.png" alt="Project Problem" width="600"/> --->

***

## 1. Description of CAD to AR Portal

### 1.1. Project Information
<img src="./images/1-1.info.png" alt="Project Information" width="700"/>

> ### About Our Client
> EXO Insights provides an industrial safety and training system using advanced AR/VR systems for energy companies in high-risk working environments

### 1.2. Problem
<img src="./images/1-2.problem.png" alt="Project Problem" width="700"/>

### 1.3. Solution
<img src="./images/1-3.solution.png" alt="Project Solution" width="700"/>

***

## 2. Technologies
<img src="./images/2.technologies.png" alt="Technologies" width="1000"/>

> ### Web Front-End
> HTML5, CSS3, jQuery, Bootstrap, AJAX
>
> ### 3D Model Display
> WebGL (threejs)
>
> ### Web Back-End
> JSP/Servlet
>
> ### Messaging System
> Data serialized in JSON over ZMQ
>
> ### 3D Model Converter
> FBX SDK(C++), CMake
>
> ### Amazon EC2
> [User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)  
> [How to Create EC2 Resources and Launch EC2 Instance](https://docs.aws.amazon.com/efs/latest/ug/gs-step-one-create-ec2-resources.html)  
> [How to add new user accounts with SSH to EC2 Linux instance](https://aws.amazon.com/premiumsupport/knowledge-center/new-user-accounts-linux-instance/?nc1=h_ls)

### 2.1. Messaging System
<img src="./images/2-1.messaging.png" alt="Messaging System" width="1000"/>

***

## 3. 3D Model Converting

### 3.1. 3D Model Structure (Example)
<img src="./images/3-1.3dmodel.transparent.png" alt="3D Model Structure Example" width="1000"/>

### 3.2. 3D Model Converting Process
> **Step-1. Load model and remove the existing materials**
> <img src="./images/3-2.step1.transparent.png" alt="3D Model Converting Step 1" width="600"/>
>
> **Step-2. Create a new material node and connect to mesh node**
> <img src="./images/3-2.step2.transparent.png" alt="3D Model Converting Step 2" width="600"/>
>
> **Step-3. Create a new texture node and connect to material node**
> <img src="./images/3-2.step3.transparent.png" alt="3D Model Converting Step 3" width="670"/>
>
> **Step-4. Traverse all child nodes and repeat Step2 and 3**
> <img src="./images/3-2.step4.transparent.png" alt="3D Model Converting Step 4" width="800"/>
>

***

## 4. Screen Shots (4 step process)
**Step-1. Upload**
<img src="./images/4.screenshot.step1.png" alt="Screenshot Step 1" width="1000"/>

**Step-2. Evaluate**
<img src="./images/4.screenshot.step2.png" alt="Screenshot Step 2" width="1000"/>

**Step-3. Convert**
<img src="./images/4.screenshot.step3-1.png" alt="Screenshot Step 3-1" width="1000"/>
<img src="./images/4.screenshot.step3-2.png" alt="Screenshot Step 3-2" width="1000"/>

**Step-4. Download**
<img src="./images/4.screenshot.step4.png" alt="Screenshot Step 4" width="1000"/>

**Output**  
<img src="./images/4.screenshot.step5.output.png" alt="Output" width="1000"/>
