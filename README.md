# Face-Recognition-Data-Collection-App
This Face Recognition application is built using Python and employs the Haar Cascade Frontal Face algorithm for facial detection. The system captures user details along with their photos, which are then utilized for training and testing during the recognition phase. The trained model enables accurate identification of individuals by comparing real-time inputs against stored facial data.  

The application leverages OpenCV for image processing, NumPy for numerical operations, and Tkinter for a user-friendly GUI interface. Additionally, it can be integrated with email notifications, attendance tracking, or security systems, making it suitable for various use cases such as employee attendance, access control, and identity verification.  

![Screenshot 2023-03-29 061932](https://user-images.githubusercontent.com/85058862/228399840-96f51484-fbc1-4b55-bfbd-49a592fc7422.png)

The "Sample" button initiates the data collection process, capturing the user's face in gray-scale format. These images are then stored and used for training the model. The application utilizes the Haar Cascade Frontal Face algorithm to detect facial features accurately.

Once sufficient sample images are collected, the model undergoes training, after which it is saved in a .yaml file format. This trained model is later used during the recognition phase, where it compares real-time input with stored facial data to identify the person.

This process ensures an efficient and accurate face recognition system, making it applicable for various use cases such as identity verification, attendance tracking, and security authentication.

![Screenshot 2023-03-29 061950](https://user-images.githubusercontent.com/85058862/228400191-621e8f9a-eb43-480d-a66d-499a686d6875.png)

![Screenshot 2023-03-29 062055](https://user-images.githubusercontent.com/85058862/228400263-0855321a-d19f-4e65-b78f-c25f412fc55d.png)

The collected user-details are stored in .csv file
![Screenshot 2023-03-29 062115](https://user-images.githubusercontent.com/85058862/228400311-33d28cd7-c58e-465f-8749-2d3bcf5f0417.png)
