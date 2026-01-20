# Problem-Solving-with-Java

A collection of Java programs demonstrating various problem-solving techniques and algorithms.

## Project Overview

This project contains multiple Java programs that solve different computational problems, ranging from basic calculations to data manipulation and pattern generation.

## Project Structure

```
src/main/java/
├── BabiesHeight.java            # Calculate babies' growth patterns
├── BinaryOrNot.java             # Check if a number is binary
├── CalculateLaptopPrice.java    # Price calculation logic
├── Count.java                   # Counting algorithms
├── CountNotes.java              # Money notes counting
├── ExtractTnxID.java            # Transaction ID extraction
├── FindValidIP.java             # IP address validation
├── GenerateNumber.java          # Number generation
├── MakePassword.java            # Password generation
├── MakePattern.java             # Pattern creation
├── MarksDistribution.java       # Grade/marks distribution
├── SearchCGPAbyBinary.java      # Binary search for CGPA
├── SecondHighestCGPA.java       # Find second highest CGPA
├── SortCGPA.java                # Sort CGPA values
├── VowelRemover.java            # Remove vowels from text
└── org/example/Main.java        # Entry point
```

## Prerequisites

- Java 8 or higher
- Gradle 8.10+

## Build Instructions

To build the project, run:

```bash
./gradlew build
```

On Windows:
```bash
gradlew.bat build
```

## Running Programs

To run a specific Java program:

```bash
java -cp build/classes/main ProgramName
```

For example:
```bash
java -cp build/classes/main VowelRemover
java -cp build/classes/main FindValidIP
java -cp build/classes/main SortCGPA
```

## What's Excluded

The following files and directories are excluded from version control:
- `build/` - Compiled classes and build artifacts
- `bin/` - Compiled binaries
- `.gradle/` - Gradle cache and build files
- `.idea/` - IDE configuration files
- `*.class` - Compiled Java classes

See `.gitignore` for the complete list.

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Shihab2062/Problem-Solving-with-Java.git
cd Problem-Solving-with-Java
```

2. Build the project:
```bash
./gradlew build
```

3. Run a program:
```bash
java -cp build/classes/main BabiesHeight
```

## Contributing

Feel free to submit issues or create pull requests for improvements.

## License

This project is open source and available under the MIT License.
