# Data Description
The primary goal of the research I am conducting is to validate a simplified model of heat transfer coefficients from boiling surfaces, with an emphasis on dielectric (non-conductive) fluids. For context, the majority of data centers around the world are primarily air cooled, and the lack of liquid cooling represents a relatively large inefficiency. Even without extensive knowledge of heat transfer, nearly everyone can identify a significant temperature difference between standing in a 70℉ room and swimming in a 70℉ pool. It happens that boiling the fluid enhances this perceived heat transfer by yet another order of magnitude. By then immersing computer processors in a fluid whose boiling point is near that of the ideal operating temperature of the processor, significant efficiency gains could be seen in cooling requirements for data centers. By studying certain behaviors of fluid flow in and around boiling surfaces we can validate a model which would allow the optimization of board design with respect to cooling capabilities much easier.  

 Obviously, the idea of immersion cooling computer components has been around for some time, however the current scaled application of immersion cooled, ie. data centers, only immerse circuit boards that have been designed and optimized for air cooling. In my research we utilize a technique known as Particle Image Velocimetry (PIV) wherein a fluorescent particle, referred to as a ‘tracer’ is injected into a fluid to be studied. A planar laser is then flashed and a single image is captured, when done in succession quickly, the resulting images will create a film with the tracers highlighting the fluid streamlines. THe resulting images are then fed into a code that creates a 3-D vector map of fluid velocities on and around the surface, which is saved as a 3-D model. The hope is that by using this technique on a boiling surface we can validate a previously postulated, simplified hydrodynamic model of a certain boiling phenomenon which would greatly improve the ability to optimize data center immersion cooling, and thus the total efficiency. 

I have not yet begun to take PIV data as I am still getting the experimental enclosure operational, however I have talked with some peers who knew previous students with PIV experiments. From my understanding one PIV project required an entire harddrive only a few years ago, so I am projecting to need at least a 1 TB of space. This is mainly to do with the hundreds of thousands if not millions of photos that need to be taken in order to get images that the MatLab code can properly parse into a vector field. 


# Roles and responsibilities

Implementation

I am currently the sole graduate student in the enhanced heat transfer laboratory currently working on the pool boiling project. Because of this, I will be solely responsible for the implementation of the data management plan. However, my advisor, Dr. Gess will also be partially responsible for making sure I am carrying out the data management as he would like to continue experiments with this enclosure after I have graduated. 

Responsibilities

I will be solely responsible for all data collection, storage, and analysis. Because of this I will be solely responsible for creating and following the data management plan. This includes keeping an up-to-date well organized box drive, which will include all meta data that I create as well as actual project data, including but not limited excel files, 3D model files, and folders filled with .JPG picture files. 

Contingencies

As the sole contributor to this project, if I were to leave the project, not only would there be no one to experiment and collect data, but also any data that I have not properly stored in the data management plan could be lost forever. To prevent this all data and meta-data is stored in an online cloud service as it is generated. This will allow all relevant project information to be accessible even if my leaving the project was abrupt and unexpected. 


Data Sensitivity

The data created, collected and analyzed during this project is the result of a corporate grant. However, the lab was given the grant as a gift, allowing Dr. Gess to choose the areas he would like to invest in. Due to this inherent freedom, I have not been required to sign a non-disclosure agreement and the corporate partner has not explicitly told us that data collected with this grant is confidential. So at the moment the data collected in this project is relatively insensitive, however this could be subject to change depending on the corporate partner’s view of the work. 

Data Storage

As per lab standard, all project information, data and meta-data included, is uploaded to a Box drive shared between Dr. Gess and I. This box file is managed by the lab so in the event Dr. Gess and myself had to leave the information, it could still be accessed and managed. Within this drive will be several types of meta-data, including the experimental code needed to perform experiments, this a LabView VI script with file extension .vi, as well as code for analyzing the collected data, which is a MatLab script with file extension .m. Beyond just code, the meta-data folder also contains experimental procedures, process diagrams of the test bed, both saved as PDF files. This folder will also contain the 3-D files of any component that needs modification and replacement, these files are generated with solid works and saved as a .STEP to ensure the files can be opened with any modeling software. As for actual data in the project, it will be separated into 2 sub-folders, one for pre and post analysis. That is one folder will be entirely raw spreadsheet data with excel file extension .xlsx which is the output of the labview scripts, while the other will be the analyzed data, still in excel .xlsx format, which is the output of the MatLab script. 

Backup Plan

For any experiment, three copies of the data will be saved. As mentioned previously one copy will be uploaded to a Box drive, one copy will be saved locally on a hard drive, and the final copy will be uploaded to an external hard drive stored in the lab. All of these locations will also store the previously mentioned meta-data. The uploading to Box can be done automatically from my lab computer, but the external save must be done by hand each time. As mentioned previously, the Box drive is owned by the lab, and thus by extension can be accessed by anyone given the permissions of our lab. This allows for the data to continue to be accessed even after I have graduated. Furthermore, the external drive is also property of the lab and will remain after my graduation. 

# Data standards and metadata
# Storage and security
# Access and data sharing
# Archiving and preservation
