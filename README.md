# 🎨 Color Detection Using OpenCV
This project detects the name of the color in an image when you double-click on any pixel. It reads RGB values, matches them to a dataset (colors.csv), and displays the closest color name.
## 📁 Project Structure
color_detect/

├── color_detection.py # Main script to run color detection

├── colorpic.jpg # Sample image for testing

├── Dogspic.jpg # Another sample image

├── solar_panel_banner1.jpg # Additional image (optional)

├── colors.csv # CSV containing predefined colors with names and RGB values

## 🧠 How It Works

1. The script uses OpenCV to display an image.
2. On double-clicking anywhere on the image, it reads the RGB values at that point.
3. It compares the clicked color with a CSV file (`colors.csv`) to find the closest matching color name.
4. The color name and RGB values are displayed on the image.

## ▶️ How to Run
### 🔧 Prerequisites

Make sure you have the following installed:

- Python 3.x
- OpenCV
- Pandas
- NumPy
Install with pip:

```bash
pip install opencv-python pandas numpy
#For running the program
python color_detection.py --image path/to/your/image.jpg
python color_detection.py --i path/to/your/image.jpg

📌 Features
Detects color names from any pixel
Displays RGB values
Works with any image
Easy to extend by modifying colors.csv

📝 Dataset - colors.csv
This file contains standard color names along with their RGB and HEX values. You can expand or replace it with your own dataset.

📸 Screenshot
output.png

🙋‍♀️ Author
Keerthana J

