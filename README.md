# Automatic License Plate Recognition (ALPR) System

## Project Overview

This project is an Automatic License Plate Recognition (ALPR) system using YOLOv8 for license plate detection and a React-based web application for visualization and user interaction. The primary goal is to detect and recognize license plates from vehicle images and display the results efficiently through a user-friendly interface.

### Project Structure

* **Machine Learning Model:** Utilizes YOLOv8 for license plate detection.
* **Web Application:** Built with React and Node.js for visualization and user interaction.
* **Data Handling:** Processes vehicle images from OLX datasets and interpolates missing data.
* **Visualization:** Graphical representation and interactive data display using the frontend.

## Installation

### Prerequisites

* Python 3.x
* Node.js and npm
* YOLOv8 (via Ultralytics)
* OpenCV, Pandas, and other Python libraries

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/username/ALPR-System.git
   cd ALPR-System
   ```
2. Install Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Set up the web application:

   ```bash
   cd miniproject
   npm install
   ```

## Usage

### Running the Model

```bash
python main.py
```

This script processes the input images and generates `test.csv` with detected license plate numbers.

### Visualizing Results

```bash
cd miniproject
npm start
```

Access the web application at `http://localhost:3000`.

## Contributions

Feel free to submit pull requests to improve the model or frontend.

## License

MIT License
