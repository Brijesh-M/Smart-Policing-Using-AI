# Smart-Policing-Using-AI

<h3>Description</h3>
This problem tackles the main problem faced by police in terms of real time monitoring of places and criminal identification..
This tool is specifically designed to enhance the monitoring system and detect any suspicious activities within the vicinity,
allowing the police department to take necessary actions to rectify the issue arised.

<h1>Usage of Intel Developer Cloud 🌐💻</h1>
Utilizing the resources provided by Intel Developer Cloud significantly expedited our AI model development and deployment processes. Specifically, we harnessed the power of Intel's CPU and XPU to accelerate two critical components of our project: Human Detection and Text-to-Outfit Generation. 💻⚡

<h3>Criminal Detection Model Training:</h3> <ol>
  <li>The Intel Developer Cloud's CPU and XPU capabilities, combined with the use of oneDNN, played a pivotal role in reducing the training time of our Human Detection model. By leveraging the high-performance computing infrastructure provided by Intel, we were able to train our model more efficiently, significantly cutting down the time required for model optimization and experimentation.🚀🔧
</li>
  <li>The integration of oneDNN, a high-performance deep learning library developed by Intel, contributed to this efficiency by optimizing the computational tasks involved in training. Notably, a single epoch now takes only 2 seconds, a substantial improvement compared to the 6 seconds it took in Colab, showcasing the remarkable speedup achieved through the use of Intel's hardware resources and optimized software stack. 🚀⚒️</li>
  <li>Additionally, the optimized version of TensorFlow tailored for Intel architectures further played a crucial role in reducing the training time. This collaborative utilization of optimized TensorFlow and Intel's advanced computing infrastructure enabled us to achieve significant improvements in model training efficiency, ultimately accelerating our development process and enhancing the overall performance of our Human Detection model. 🏋️‍♂️🧑‍💻</li>
</ol>

<h1>Alerting the Officials</h1>
Once the criminal or any suspicious activities have been captured by the model...It will also capture the location details using the GPRS mechanism.
Based on the geo location of the incident...the model will decide on which station to inform to be able to act to the inident ASAP.

<h3>There are two kinds of alerts given by this model</h3>
<ol>
  <li>Through in App notification on Station incharges</li>
  <li>Markings on radar/Map displayed on the station</li>
</ol>

<h1>Future Additions</h1>
This model has many ways to improve and enhance the policing system
<ol>
  <li>Implementaion of app on civilians to further alert them on their surroundings</li>
  <li>Setting up safe location markers to denote areas that are currently safe from intruders</li>
</ol>
