# SMaster - Sign Language Learning App

SMaster is an interactive learning application designed to teach sign language with real-time action detection. It consists of multiple components working together to provide a seamless experience for users.

## Project Structure
This project is divided into four main components, each hosted in a separate repository:

1. **[Admin Client](https://github.com/studentofmusk/SMaster-ADMIN)** - A web-based platform for managing courses.
2. **[ML Flask Server](https://github.com/studentofmusk/SMaster-ML-SERVER)** - A machine learning server for real-time action detection.
3. **[Node.js Server](https://github.com/studentofmusk/SMaster-SERVER)** - The backend server managing user interactions and course data.
4. **[React Native Application](https://github.com/studentofmusk/SMaster-APP)** - The mobile application for users to learn sign language interactively.

## Installation and Setup

### Clone the Main Repository
This repository serves as an overview and does not contain the actual code. Clone the sub-repositories separately:

```sh
# Clone all components manually
git clone https://github.com/studentofmusk/SMaster-APP
git clone https://github.com/studentofmusk/SMaster-ADMIN
git clone https://github.com/studentofmusk/SMaster-SERVER
git clone https://github.com/studentofmusk/SMaster-ML-SERVER
```

Alternatively, if using **Git submodules**, initialize all repositories with:

```sh
git clone --recurse-submodules https://github.com/studentofmusk/SMaster
```

### Running Each Component
#### **Admin Client** (React Web App)
```sh
cd SMaster-ADMIN
npm install
npm start
```

#### **ML Flask Server**
```sh
cd SMaster-ML-SERVER
pip install -r requirements.txt
python app.py
```

#### **Node.js Server**
```sh
cd SMaster-SERVER
npm install
npm start
```

#### **React Native Application**
```sh
cd SMaster-APP
npm install
npx expo start
```

## Architecture Overview
SMaster integrates multiple technologies:
- **React & React Native** for UI/UX.
- **Node.js & Express** for backend management.
- **Flask & Mediapipe** for real-time sign detection.
- **MongoDB** for storing user data and courses.


## Contributors
Thanks to the amazing team behind SMaster:

- [@studentofmusk](https://github.com/studentofmusk) — 🧠 Project Architect, Full Stack Developer (MERN Stack), AI/ML Engineer,  React Native Developer.
- [@Jasminecinthiya-5123](https://github.com/Jasminecinthiya-5123) — 🎨 UI/UX Designer.
- [@Kaviyarasi06](https://github.com/Kaviyarasi06) — 🤖 Machine Learning Engineer, Action Detection Model (Flask + Mediapipe).  
- [@Jawahar047](https://github.com/Jawahar047) — 📊 Data Collection & Dataset Management  
- [@Jasminecinthiya-5123](https://github.com/Jasminecinthiya-5123), [@Kaviyarasi06](https://github.com/Kaviyarasi06) — 📚 Course Content Curation & Testing  

  
## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For any inquiries, reach out via GitHub issues or email at `farooqkhan07122003@gmail.com`.

