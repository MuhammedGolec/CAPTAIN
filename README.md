
# CAPTAIN
CAPTAIN: A Testbed for Co-Simulation of Scalable Serverless Computing Environments for AIoT Enabled Predictive Maintenance in Industry 4.0

IIoT applications are a critical technology for the realization of Industry 4.0 and require sustainable solutions because they generate enormous amounts of data. One of these solutions is serverless computing, which has recently attracted attention in academia and the private sector. Serverless computing provides energy and cost efficiency by scaling empty containers to zero. However, the zero-scaling technology is also the main reason for the cold start issue that still awaits a solution in serverless computing. Most of the literature studies on this problem include solutions that require unnecessary resource consumption, such as keeping containers warm. The CAPTAIN framework aims to both reduce cold starts in serverless computing and provide a more sustainable solution in Industry 4.0 with a new approach that does not require resources to work in vain.

![CAPTAINMAIN](https://github.com/user-attachments/assets/2d924e3b-dcca-439f-8926-1e262a0471a3)
![CAPTAINARCH](https://github.com/user-attachments/assets/84287969-d734-4cb6-b18e-b747d99ea3fb)


 

CAPTAIN framework consists of two main modules, AI and Proxy, and is positioned between the client and the server. The proxy module records transaction information (date, latency, etc.) by monitoring all traffic between the client and the server. Then, the AI ​​Module in the CAPTAIN Framework is trained using this information. The main task of the AI ​​module is to predict possible cold start times by making time-series predictions and to make the containers operational by sending PING to the server. Thus, it is aimed to reduce the frequency of cold starts. Figure 1 and Figure 2 show the Main Diagram and Architecture for the CAPTAIN framework. For more details, please see the paper.


## Datasets

In this paper, two different cold start datasets were used in the experiments on cold start prediction and prevention. For this reason, two different Jupyter Notebook files were created for the two datasets. The first dataset is the Predictive Maintenance Dataset, and the second dataset is the Microsoft Azure Dataset. The datasets used in the CAPTAIN framework are given below.

1) Predictive Maintenance Dataset: https://github.com/MuhammedGolec/Cold-Start-Dataset-V2 

2) Azure Dataset: https://github.com/Azure/AzurePublicDataset



Warning: The copyright of the shared work is reserved. Reference should be cite to the CAPTAIN article for use in academic studies. 

To cite:
M. Golec, H. Wu, R. Ozturac, A. Parlikad, F. Cuadrado, S. S. Gill and S. Uhlig "CAPTAIN: AIoT Enabled Scalable Serverless Computing Framework for Predictive Maintenance in Industry 4.0" in IEEE Internet of Things Journal, doi: XXXX.

# Developer:
**Muhammed Göleç** <br/> 
mail: *muhammedgolec@hotmail.com* <br/>
Linkedin: [https://www.linkedin.com/in/muhammed-golec-b55756119/] <br/>
Github: [https://github.com/Muhammed1616]() 

**Rıdvan Özturaç** <br/> 
mail: *rdvan1994@gmail.com* <br/>
Linkedin: [https://www.linkedin.com/in/rozturac/] <br/>
Github: [https://github.com/rozturac]()
