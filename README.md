# SecureComm: Python GUI for Message Encryption and Decryption using Images

SecureComm is a user-friendly Python-based graphical user interface (GUI) application designed to enhance communication security through message encryption and decryption using image format files. Leveraging the power of OpenCV for image processing, this project ensures that sensitive information remains confidential during transmission.

## Features

- **Message Encryption**: Convert plain text messages into encrypted images, making the content unreadable to unauthorized recipients.
- **Message Decryption**: Decrypt encrypted images back into plain text messages, ensuring the original content can be accessed by authorized users.
- **Authentication System**: Implement a robust authentication system to validate users and prevent unauthorized access to the application.
- **Image Processing**: Utilize OpenCV to process images efficiently, ensuring seamless integration of text and images for secure communication.

## How it Works

1. **User Authentication**: Users are required to authenticate themselves before gaining access to the application. This step ensures that only authorized individuals can use the encryption and decryption features.

2. **Message Encryption**:
   - Input: Plain text message, encryption key
   - The application takes a plain text message provided by the user.
   - Using a chosen encryption key, the message is transformed into an encrypted format.
   - The encrypted message is embedded into an image using image processing techniques.
   - The resulting encrypted image is saved and can be safely shared with the intended recipient.

3. **Message Decryption**:
   - Input: Encrypted image, decryption key
   - The user provides an encrypted image and the corresponding decryption key.
   - The application extracts the encrypted message from the image.
   - Using the decryption key, the encrypted message is converted back to plain text.
   - The decrypted message is displayed to the user for further use.

## Usage

1. Launch the application.
2. Authenticate using your credentials.
3. Choose between encryption and decryption modes.
4. View the results and securely transmit your messages.

---

By combining the power of OpenCV for image processing and an authentication system, SecureComm provides a comprehensive solution for secure communication through encrypted images. Whether it's confidential messages or sensitive data, SecureComm ensures that your information remains protected during transmission.
