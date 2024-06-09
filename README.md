

# Car Number Plate Detection and Information Retrival System

This project utilizes Google Generative AI to detect car number plates from images. The number plates are extracted from images and matched with a list of names to provide corresponding information.

## Installation

### Clone the repository
```
git clone https://github.com/your-username/car-number-plate-detection.git
cd car-number-plate-detection
```

### Install dependencies
```
pip install -r requirements.txt
```

## Usage

1. **Prepare your Kaggle environment:**

   Ensure that you have access to the Kaggle environment with the necessary files. The images should be located in the `/kaggle/input/car-plate-detection/images` directory.

2. **Run the script:**

   Execute the script to detect number plates from images and match them with corresponding names:
   ```python
   python detect_number_plates.py
   ```

3. **Predict specific image:**

   Use the `predict` function to get the number plate and corresponding name for a specific image:
   ```python
   from detect_number_plates import predict

   predict('/kaggle/input/car-plate-detection/images/Cars393.png')
   ```

## Project Structure

- `detect_number_plates.py`: Main script to detect number plates and save the results.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### requirements.txt

```
numpy
pandas
pillow
langchain_google_genai
langchain_core
google.generativeai
```

---
