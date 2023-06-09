# Welcome to the Capstone-RSD GitHub organization 👋! 

Our aim is to design, build and deploy a distributed solution that can capture, classify and provide a means to react to various road damages in realtime. Below, you'll find an overview of our projects and their respective functionalities.

## Projects

The following projects are a part of the Road Surface Deterioration 2023 Capstone project at Ontario Tech University.

<details>
  <summary>Capstone-RSD/rss-client</summary>
  
### Capstone-RSD/rss-client

- [Repository](https://github.com/Capstone-RSD/rss-client)
- Description: This Flutter mobile application allows users to capture and upload the road damage encountered to a cloud storage bucket, and simultaenously publish an event to our deployed event streaming platform in the cloud. It includes features such as authentication, and a user-friendly interface.
</details>

<details>
  <summary>Capstone-RSD/rsd-dashboard</summary>

### Capstone-RSD/rsd-dashboard

- [Repository](https://github.com/Capstone-RSD/rsd-dashboard)
- Description: This flutter web application which renders details of the classified Road Conditions on a map along with it location.
</details>

 <details>
  <summary>Capstone-RSD/rsd-yolov5-model</summary>
 
### Capstone-RSD/rsd-yolov5-model

- [Repository](https://github.com/Capstone-RSD/rsd-yolov5-model)
- Description: This Python project focuses on detecting irregularities in road surfaces using computer vision techniques. It includes code for subscribing to events from Apache Kafka event streaming platform, performing infrencing on the image payload, storing the ouput in a graph database, and generating a pin on openstreetmaps for the dashboard application.
</details>

 <details>
  <summary>Capstone-RSD/rsd-src-generator</summary>
 
### Capstone-RSD/rsd-src-generator

- [Repository](https://github.com/Capstone-RSD/rsd-src-generator)
- Description: This project is dedicated to generating source code from a protocol buffer schema. The repository includes an action workflow that will generate the source code and make available to download upon a push to the repository. The current working schema is [rss_schema.proto](https://github.com/Capstone-RSD/rsd-src-generator/blob/main/rss_schema.proto)
</details>

## Video Recordings
<details>
  <summary>Capstone-RSD/Capstone-Exhibition-Project Video Recording</summary>

We have video recordings available that showcase the functionality and usage of our projects:
[<img src="https://img.youtube.com/vi/XeFbU0Z5jmM/maxresdefault.jpg" width="50%">](https://youtu.be/XeFbU0Z5jmM)
</details>

## Contact Information

If you have any questions, suggestions, or inquiries regarding our projects, feel free to reach out to us:

- Email: [tiwaloluwa.ojo@ontariotechu.net](mailto:tiwaloluwa.ojo@ontariotechu.net)
