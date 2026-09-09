# 🚨 Desh Seva – Emergency & Disaster Response Platform

## 🌍 About the Project

**Desh Seva** is an emergency and disaster response platform designed to help connect people in distress with nearby emergency services and organizations.

During an accident, natural disaster, or other emergency situation, quick communication and coordination can save lives. **Desh Seva aims to reduce the delay in emergency response** by providing a centralized platform where emergency situations can be reported and communicated to relevant nearby organizations.

The platform helps connect emergency incidents with:

* 🏥 Nearby Hospitals
* 🚒 Fire Brigades
* 🤝 NGOs
* 🧑‍🚒 Volunteers
* 🚑 Emergency Response Services

When an emergency or disaster is reported, the system can display the incident location and surrounding emergency resources on a map. The emergency situation is categorized according to its seriousness using a **Red, Yellow, and Green severity system**, helping responders understand which situations require immediate attention.

---

# 🎯 Problem Statement

During accidents and disasters, people often face several problems:

* Difficulty contacting the correct emergency service.
* Delays in informing nearby hospitals or organizations.
* Lack of coordination between volunteers and emergency responders.
* Difficulty identifying the exact location of an emergency.
* Lack of a centralized platform for disaster reporting and emergency assistance.

In critical situations, even a few minutes of delay can make a significant difference.

**Desh Seva was developed to provide a centralized emergency communication and response platform that can help connect affected people with nearby organizations and resources.**

---

# 💡 Solution

Desh Seva provides a platform where emergency and disaster-related information can be reported and visualized.

The system focuses on:

1. Reporting an accident or disaster.
2. Identifying the emergency location.
3. Displaying emergency information on Google Maps.
4. Showing nearby hospitals, NGOs, volunteers, and other emergency resources.
5. Categorizing emergencies based on their seriousness.
6. Helping relevant organizations receive emergency information quickly.
7. Providing useful disaster and emergency-response resources to users.

---

# 🗺️ Emergency Location & Google Maps

One of the important features of **Desh Seva** is the integration of the **Google Maps API**.

Google Maps helps visualize:

* 📍 Emergency locations
* 🏥 Nearby hospitals
* 🤝 NGOs and support organizations
* 🚒 Fire and emergency services
* 🧑‍🤝‍🧑 Volunteers and available resources

Displaying emergency information on a map makes it easier to understand the location and seriousness of an incident.

---

# 🚦 Emergency Severity Levels

Desh Seva uses a simple color-based system to represent the seriousness of an emergency.

## 🔴 Red – Critical Emergency

The **Red** level represents highly serious or life-threatening situations that require immediate emergency response.

Examples:

* Major accidents
* Severe disasters
* Large-scale emergencies
* Situations requiring immediate medical or rescue assistance

---

## 🟡 Yellow – Moderate Emergency

The **Yellow** level represents situations that require attention and assistance but may not be as critical as Red-level emergencies.

Examples:

* Moderate accidents
* Local emergency situations
* Situations requiring NGO or volunteer assistance

---

## 🟢 Green – Low Severity / Manageable Situation

The **Green** level represents lower-risk situations where immediate large-scale emergency intervention may not be required.

Examples:

* Minor incidents
* Situations requiring support or monitoring
* Non-critical assistance requests

---

# ✨ Key Features

## 🚨 Disaster and Emergency Reporting

Users can report accidents or disasters through the platform.

Emergency information can include:

* Type of emergency
* Location
* Description of the situation
* Severity level
* Required assistance

This information can help communicate the situation to relevant responders.

---

## 🏥 Nearby Hospital Information

Desh Seva provides information related to nearby hospitals and emergency medical assistance.

This feature aims to help users quickly identify available medical resources during an emergency.

---

## 🤝 NGO Information and Support

The platform includes information about NGOs and organizations that can provide support during disasters and emergency situations.

Users can access NGO-related information and contact details to seek assistance or coordinate relief efforts.

---

## 🧑‍🚒 Volunteer Participation

Desh Seva encourages volunteers to participate in emergency and disaster response.

Volunteers can become part of the support network and assist in situations where additional help is required.

The platform includes volunteer-related functionality and login pages to support volunteer participation.

---

## 🚒 Emergency Services

The project is designed around the idea of connecting emergency situations with important response services such as:

* Hospitals
* Fire Brigades
* NGOs
* Volunteers
* Other emergency responders

This centralized approach can help improve communication during critical situations.

---

## 🤖 Emergency Assistance Chatbot

The project also includes a chatbot feature that can help users access information and assistance more easily.

The chatbot can improve the user experience by providing quick guidance and directing users toward useful emergency resources.

---

## 📚 Emergency Learning Resources

Desh Seva provides educational and informational resources related to emergency preparedness and disaster response.

These resources can help users learn about:

* Basic emergency response
* Disaster awareness
* First-aid-related information
* Safety precautions
* Emergency preparedness

---

## 💰 Donation Support

The project also includes a donation-related section.

During disasters, donations can play an important role in supporting affected communities and relief activities. This feature provides a space for users to explore and support disaster-relief efforts.

---

# 🛠️ Technologies Used

The project is built using web technologies, including:

### Frontend

* HTML5
* CSS3
* JavaScript

### APIs and Services

* Google Maps API

### Project Components

* Google Maps Integration
* Emergency Reporting System
* NGO Information
* Volunteer System
* Disaster Reporting
* Emergency Severity Visualization
* Chatbot
* Donation Page
* Learning and Resource Pages

---

# 📂 Project Structure

```text
Desh-Seva/
│
├── index.html                 # Main/Home Page
├── style.css                  # Main Styling
├── app.js                     # Main JavaScript
│
├── disaster report.html       # Disaster Reporting Page
├── disaster.css               # Disaster Page Styling
├── disaster.js                # Disaster Page Functionality
│
├── DelhiNgo_list.html         # NGO Information
├── NGO.html                   # NGO Page
├── NGO1_CONT.HTML             # NGO Contact Information
├── NGO2_CONT.html
├── NGO3_CONT.html
├── NGO4_CONT.html
│
├── vol_login.html             # Volunteer Login
│
├── chatbot.html               # Emergency Chatbot
│
├── donation page.html         # Donation Page
├── donation.css
├── donation.js
│
├── learn.html                 # Learning Resources
├── learn.css
├── learn.js
│
├── resources.html             # Emergency Resources
├── resource.css
│
├── images/                    # Images and Media Assets
│
└── README.md
```

---

# 🚀 How to Run the Project

Follow these steps to run the project locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/mohi-008/hackathon.git
```

### Step 2: Open the Project Folder

```bash
cd hackathon
```

### Step 3: Open the Project

Open the project folder in:

* Visual Studio Code
* Any code editor

### Step 4: Run the Website

Open:

```text
index.html
```

You can run the project directly in your browser or use the **Live Server** extension in Visual Studio Code.

---

# 🔑 Google Maps API Setup

To use the Google Maps functionality, you may need a valid Google Maps API key.

### Steps:

1. Create a project in Google Cloud.
2. Enable the required Google Maps APIs.
3. Generate an API key.
4. Add the API key to the required project configuration or JavaScript file.
5. Make sure API key restrictions are configured properly.

> ⚠️ **Security Note:** Never upload private API keys directly to a public GitHub repository. Use environment variables or appropriate API key restrictions whenever possible.

---

# 🔄 How Desh Seva Works

```text
Emergency / Disaster Occurs
            │
            ▼
User Reports the Emergency
            │
            ▼
Emergency Location is Identified
            │
            ▼
Incident is Displayed on Google Maps
            │
            ▼
Severity is Categorized
   🔴 Red | 🟡 Yellow | 🟢 Green
            │
            ▼
Nearby Emergency Resources are Identified
            │
            ├── 🏥 Hospitals
            ├── 🤝 NGOs
            ├── 🚒 Fire Services
            └── 🧑‍🚒 Volunteers
            │
            ▼
Emergency Information Can Be Shared
with Relevant Responders
```

---

# 🎯 Future Improvements

Desh Seva can be improved further by adding:

* 📱 Real-time emergency notifications
* 📍 Automatic live location detection
* 🔔 SMS and email alerts
* 📲 Mobile application support
* 🚑 Real-time ambulance availability
* 🏥 Hospital bed availability
* 👮 Police station integration
* 🔥 Direct fire brigade notification
* 🤖 AI-based emergency severity prediction
* 🌐 Real-time disaster monitoring
* 🧑‍🤝‍🧑 Volunteer availability tracking
* 📊 Emergency response analytics
* 🔐 Secure user authentication
* ☁️ Database integration for real-time emergency data

---

# 🌟 Vision

The vision of **Desh Seva** is to create a connected emergency-response ecosystem where technology helps reduce communication delays and connects people with the right resources during critical situations.

By combining location-based services, emergency reporting, NGOs, volunteers, hospitals, and disaster resources, the platform aims to support faster and more organized emergency response.

> **"In an emergency, every second matters. Desh Seva aims to connect people, resources, and responders when help is needed the most."**

---

# 🤝 Contributing

Contributions, ideas, and suggestions are welcome.

If you would like to improve the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Create a Pull Request.

---

# 📄 License

This project is currently created for educational and development purposes.

You can add an appropriate open-source license in the future, such as the MIT License.

---

# 👨‍💻 Author

**Mohit Kumar**

GitHub: `https://github.com/mohi-008`

---

## ⭐ Support

If you like this project, consider giving the repository a **⭐ Star** on GitHub!

Your support and feedback will help improve **Desh Seva** and its mission of building a better emergency and disaster response platform.
