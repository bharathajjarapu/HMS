# ArcHospital
Hospital DBMS

Welcome to the Hospital Data Management System! This Flask application provides a comprehensive solution for managing doctors 👩‍⚕️👨‍⚕️, patients 🧑, appointments 📅, and medical records 📝 in a hospital environment. With its user-friendly interface and robust backend, this system streamlines the entire healthcare workflow, enabling efficient management of hospital operations. 🚀

## Features 🌟

- **Doctor Management**: Add 👥, view 👀, and delete ❌ doctor profiles with their specialties and contact information.
- **Patient Management**: Maintain a database of patients 🧑 with their personal details and medical histories. 📂
- **Appointment Scheduling**: Schedule appointments 📆 by assigning doctors to patients based on availability and specialties.
- **Medical Records**: Store 💾 and retrieve 📥 detailed medical records for each patient.
- **Automatic Appointment Assignment**: Leverage an intelligent algorithm 🤖 to automatically assign appointments based on doctor specialties and patient medical histories.

## Installation 💻

1. Clone the repository:

```bash
git clone https://github.com/your-username/hospital-management-system.git
```

2. Navigate to the project directory:

```bash
cd hospital-management-system
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Set up the SQLite database:

```bash
python
>>> import sqlite3
>>> conn = sqlite3.connect('archospital.db')
>>> conn.close()
```

5. Run the Flask application:

```bash
python app.py
```

The application will be accessible at [`http://localhost:5000`](http://localhost:5000).

## Usage 🧑‍💻

1. **Homepage**: The landing page provides an overview of the Hospital Management System. 🏠
2. **Doctors**: Access the list of registered doctors 👩‍⚕️👨‍⚕️. You can add new doctors 👥, view their details 👀, and delete existing ones ❌.
3. **Patients**: Manage the patient database 🧑. Add new patients 👥, view their medical histories 📜, and remove existing patients ❌.
4. **Appointments**: Schedule appointments 📅 by assigning doctors to patients based on availability and specialties. View the list of scheduled appointments 📋, and delete appointments if needed ❌.
5. **Auto-Assign Appointments**: Use the intelligent algorithm 🤖 to automatically assign appointments based on doctor specialties and patient medical histories.

## Contributing 🤝

Contributions are welcome! If you have any ideas 💡, bug reports 🐛, or feature requests ✨, please open an issue or submit a pull request.

## License 📜

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments 🎶

- [Flask](https://flask.palletsprojects.com/) - The Python web framework used for this project.
- [SQLite](https://www.sqlite.org/) - The embedded database engine used for data storage.

Feel free to explore the HMS and enhance it with additional features or improvements! Happy coding! 🏥✨