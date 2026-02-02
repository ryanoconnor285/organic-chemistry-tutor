# 🧪 Organic Chemistry Tutor

A web-based interactive application designed to help students learn organic chemistry through practice and engagement. The first module focuses on IUPAC (International Union of Pure and Applied Chemistry) naming conventions for carbon chains.

## Features

### IUPAC Naming Module - Carbon Chains

- **Dynamic Molecule Generation**: Automatically generates skeletal structures for alkane molecules
- **Multiple Difficulty Levels**:
  - **Easy**: 1-4 carbon atoms (methane, ethane, propane, butane)
  - **Medium**: 5-7 carbon atoms (pentane, hexane, heptane)
  - **Hard**: 8-10 carbon atoms (octane, nonane, decane)
- **Interactive Learning**: Visual skeletal structure representation with real-time feedback
- **Progress Tracking**: Score system and statistics (correct answers, total attempts)
- **User-Friendly Interface**: Clean, modern design with helpful hints

## How to Use

### Running the Application

1. **Open the application**: Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
   ```bash
   # Option 1: Double-click index.html in your file explorer
   
   # Option 2: Use a local server (recommended for development)
   python -m http.server 8000
   # Then navigate to http://localhost:8000 in your browser
   ```

2. **Select difficulty**: Choose from Easy, Medium, or Hard based on your skill level

3. **Study the molecule**: A skeletal structure will be displayed showing the carbon chain

4. **Enter your answer**: Type the IUPAC name (e.g., "propane", "hexane", "decane")

5. **Submit**: Click "Submit Answer" or press Enter to check your answer

6. **Learn**: Get immediate feedback with the correct answer if you're wrong

7. **Continue**: The app automatically generates a new molecule after each answer

## Understanding Skeletal Structures

In skeletal structures:
- Each vertex (corner/endpoint) represents a carbon atom
- Carbon atoms are implied at vertices and not explicitly shown
- Hydrogen atoms are implicit and satisfy carbon's valency (4 bonds)
- Only the carbon backbone is drawn
- Terminal carbons (ends) have CH₃ groups, middle carbons have CH₂ groups

## IUPAC Naming Rules - Alkanes

Alkanes are hydrocarbons with single bonds between carbon atoms. The name is based on the number of carbons:

| Carbons | IUPAC Name |
|---------|------------|
| 1       | Methane    |
| 2       | Ethane     |
| 3       | Propane    |
| 4       | Butane     |
| 5       | Pentane    |
| 6       | Hexane     |
| 7       | Heptane    |
| 8       | Octane     |
| 9       | Nonane     |
| 10      | Decane     |

## Technical Details

### Technology Stack
- **HTML5**: Structure and Canvas API for drawing
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: No external dependencies required

### Browser Compatibility
- Chrome/Edge: ✅ Fully supported
- Firefox: ✅ Fully supported
- Safari: ✅ Fully supported
- Mobile browsers: ✅ Responsive design

## Future Enhancements

Planned features for future releases:
- Branched carbon chains (isomers)
- Functional groups (alcohols, aldehydes, ketones, carboxylic acids)
- Multiple bonds (alkenes, alkynes)
- Cyclic structures
- Practice mode with unlimited attempts
- Timed challenges
- Leaderboard system
- More detailed explanations and tutorials

## Contributing

This is an educational project. Contributions are welcome! Please feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## License

This project is open source and available for educational purposes.