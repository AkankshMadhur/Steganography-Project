# Image Steganography with Python

This project demonstrates how to conceal and retrieve secret messages within images using Python's OpenCV library. It modifies pixel values to embed text while ensuring minimal alteration to the original image quality.

## Features

- **Message Embedding**: Hide a secret message within an image by modifying pixel values.
- **Password Protection**: Secure the hidden message with a user-defined passcode.
- **Message Extraction**: Retrieve and display the concealed message from the image using the correct passcode.

## Requirements

- Python 3.10
- OpenCV (`opencv-python`)
- Tkinter (built-in with Python)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AkankshMadhur/Steganography-Project.git
   cd Steganography-Project
   ```

2. **Install the required packages:**
   ```bash
   pip install opencv-python
   ```

## Usage

1. **Prepare an Image:**
   - Select an image file (`.jpg`, `.png`, `.jpeg`) for embedding a message.

2. **Run the Script:**
   ```bash
   python stego.py
   ```

3. **Follow the Prompts:**
   - **Encoding:** Enter a secret message and passcode. The message will be embedded into the image and saved as `encryptedImage.jpg`.
   - **Decoding:** Provide the correct passcode to retrieve and display the hidden message.

## Methodology

This project modifies pixel values to store text, ensuring that the visual changes are imperceptible to the human eye. The process maintains the image’s integrity while enabling secure message hiding and retrieval.

## Limitations

- **Message Length**: The image size must be sufficient to store the entire message.
- **Security**: While basic password protection is included, stronger encryption methods can enhance security.

## License

No License.

