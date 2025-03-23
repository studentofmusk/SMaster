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
git clone <admin_client_repo_url>
git clone <ml_flask_server_repo_url>
git clone <node_server_repo_url>
git clone <react_native_app_repo_url>
```

Alternatively, if using **Git submodules**, initialize all repositories with:

```sh
git clone --recurse-submodules <main_repo_url>
```

### Running Each Component
#### **Admin Client** (React Web App)
```sh
cd admin-client
npm install
npm start
```

#### **ML Flask Server**
```sh
cd ml-flask-server
pip install -r requirements.txt
python app.py
```

#### **Node.js Server**
```sh
cd node-server
npm install
npm start
```

#### **React Native Application**
```sh
cd react-native-app
npm install
npx expo start
```

## Architecture Overview
SMaster integrates multiple technologies:
- **React & React Native** for UI/UX.
- **Node.js & Express** for backend management.
- **Flask & Mediapipe** for real-time sign detection.
- **MongoDB** for storing user data and courses.
- **MQTT/WebSockets** (if applicable) for real-time communication.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes.
4. Submit a pull request.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For any inquiries, reach out via GitHub issues or email at `your_email@example.com`.

