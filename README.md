# EduScan

EduScan is an intelligent student dress code and compliance monitoring system designed for colleges and schools. It automatically detects violations such as improper dress code, missing helmets, or absent ID cards, and sends real-time alerts to administrators for quick action.

## Features

- **Automated Dress Code Detection:** Uses advanced computer vision to monitor and identify students who are not adhering to the prescribed dress code.
- **Helmet & ID Card Check:** Detects if students are missing helmets (for riders) or ID cards.
- **Real-Time Alerts:** Instantly notifies admin or authorized personnel when a violation is detected.
- **Dashboard & Logs:** Provides an administrative interface to review alerts, view statistics, and manage records.
- **Customizable Rules:** Adaptable to different institutional policies and requirements.

## How It Works

1. **Monitoring:** Cameras placed at entry points or strategic locations capture images or video streams of students.
2. **Detection:** EduScan processes the feeds to identify dress code violations, missing helmets, and ID cards using AI models.
3. **Alerting:** Upon detecting a violation, the system generates a real-time alert and notifies the admin via dashboard, email, or SMS.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Pranavborade17/Eduscan.git
   cd Eduscan
   ```
2. Install dependencies:
   ```bash
   # Example for Python projects
   pip install -r requirements.txt
   ```
   *(Adjust the above line as per your tech stack)*

3. Configure cameras and admin notification settings in the configuration file.

## Usage

- Start the main application:
  ```bash
  python main.py
  ```
  *(Replace with your actual entry point if different)*

- Access the admin dashboard via the provided URL or app interface.

## Customization

- Update dress code, helmet, and ID card rules in the configuration file to suit your institution’s policies.
- Integrate with additional alert channels (e.g., WhatsApp, push notifications) as needed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or feature requests.

## License

This project is licensed under the MIT License.

## Contact

For support or business inquiries, contact [Pranavborade17](https://github.com/Pranavborade17).

---
