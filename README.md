# 🧮 Matrix Calculator

A powerful, interactive matrix calculator with step-by-step explanations designed for students learning linear algebra. Features matrix operations, encoding/decoding capabilities, and a clean, modern interface.

🌐 **Live Demo**: [https://amsayeed.github.io/matrix-calc/](https://amsayeed.github.io/matrix-calc/)

![Matrix Calculator](https://img.shields.io/badge/Matrix-Calculator-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

### 📊 Matrix Operations
- **Addition & Subtraction** - Add or subtract matrices of the same dimensions
- **Multiplication** - Multiply compatible matrices (A×B where A's columns = B's rows)
- **Division** - Divide matrices by multiplying with the inverse (A÷B = A×B⁻¹)
- **Determinant** - Calculate determinant for square matrices (1×1, 2×2, 3×3)
- **Inverse** - Find the inverse of square matrices
- **Trace** - Sum of diagonal elements

### 🎯 Key Features
- **Flexible Matrix Sizes** - Support for any matrix size from 1×1 to 3×3
- **Non-Square Matrices** - Handle rectangular matrices like 2×3, 3×1, etc.
- **Step-by-Step Solutions** - Detailed explanations for every calculation
- **Smart Operation Filtering** - Only shows valid operations for current matrix dimensions
- **Interactive Controls**:
  - Quick +1/-1 buttons to modify all matrix elements
  - Clear button to reset matrices to zero
  - Identity button to create identity matrices
  - Enable/disable individual matrices with checkboxes

### 🔐 Encoding/Decoding (2×2 matrices only)
- Encode text messages into numbers using matrix multiplication
- Decode number sequences back to text
- Visual step-by-step encryption process
- Copy-friendly output format

## 🚀 Getting Started

### Online Usage
Simply visit [https://amsayeed.github.io/matrix-calc/](https://amsayeed.github.io/matrix-calc/) to start using the calculator.

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/amsayeed/matrix-calc.git
   cd matrix-calc
   ```

2. Open `index.html` in your web browser:
   ```bash
   open index.html  # macOS
   # or
   start index.html  # Windows
   # or
   xdg-open index.html  # Linux
   ```

## 💡 How to Use

### Basic Matrix Operations
1. **Set Matrix Sizes**: Choose rows and columns for Matrix A and Matrix B
2. **Enter Values**: Input numbers into the matrix cells
3. **Select Operation**: The dropdown automatically shows compatible operations
4. **Calculate**: Click the Calculate button to see results with explanations

### Quick Controls
- **+1 Button**: Adds 1 to all elements in the matrix
- **-1 Button**: Subtracts 1 from all elements
- **Clear**: Sets all elements to 0
- **Identity**: Creates an identity matrix (1s on diagonal)

### Message Encoding/Decoding
1. Select "Encode Text → Numbers" or "Decode Numbers → Text"
2. Enter your message (letters only for encoding)
3. Set your 2×2 encoding matrix
4. Click Process to see the result
5. Use the Copy button to save encoded output

## 🎨 User Interface

The calculator features a modern, clean design with:
- 🎯 Gradient backgrounds and smooth animations
- 📱 Fully responsive design for all devices
- 🎨 Color-coded buttons and visual feedback
- 📊 Clear matrix visualization with borders
- ✨ Step-by-step explanations in highlighted boxes

## 🛠️ Technical Details

### Built With
- **HTML5** - Structure and layout
- **CSS3** - Styling with modern features (gradients, animations, flexbox)
- **Vanilla JavaScript** - No dependencies, pure JavaScript implementation

### Browser Compatibility
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📸 Screenshots

### Matrix Operations
The main calculator interface showing matrix operations with step-by-step solutions.

### Encoding/Decoding
Text encoding and decoding feature with visual explanations.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more matrix operations (eigenvalues, QR decomposition, etc.)
- Support for larger matrices (4×4 and beyond)
- Export results to PDF or image
- Save/load matrix configurations
- Add more encoding algorithms
- Implement matrix visualization graphs

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Designed for students learning linear algebra
- Inspired by the need for clear, step-by-step mathematical explanations
- Built with education and accessibility in mind

## 📧 Contact

Ahmed Sayed - [@amsayeed](https://github.com/amsayeed)

Project Link: [https://github.com/amsayeed/matrix-calc](https://github.com/amsayeed/matrix-calc)

---

<p align="center">Made with ❤️ for math students everywhere</p>