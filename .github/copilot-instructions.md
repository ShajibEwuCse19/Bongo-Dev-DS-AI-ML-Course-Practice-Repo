# Copilot Instructions for Python_Practice

## Project Overview
This is a Python learning and practice workspace. The focus is on implementing Python exercises and algorithms for skill development in data structures, algorithms, and machine learning concepts.

## File Structure & Purpose
- **practice1.py** - Core practice exercises and implementations
- Expand with additional `practice*.py` files as more exercises are added
- Follow a modular approach: one primary concept/exercise per file

## Development Workflow

### Running Scripts
```powershell
# Execute any Python script from PowerShell terminal
python practice1.py
```

### Execution Patterns
- Each script should be self-contained and runnable with `python filename.py`
- Include example outputs or test cases inline for quick validation
- Use `if __name__ == "__main__":` guard for main execution blocks

## Coding Conventions

### Style & Structure
- Follow PEP 8 for naming: `snake_case` for functions/variables, `PascalCase` for classes
- Add docstrings to functions explaining inputs, outputs, and purpose
- Include inline comments for complex logic or non-obvious algorithm steps
- Separate exercises with clear section comments (e.g., `# Exercise: Problem Name`)

### Algorithm Documentation
When implementing algorithms or data structures:
```python
def algorithm_name(param1, param2):
    """
    Brief description of what the algorithm does.
    
    Args:
        param1: Description of first parameter
        param2: Description of second parameter
    
    Returns:
        Description of return value
    
    Time Complexity: O(n)
    Space Complexity: O(1)
    """
    # Implementation
```

## Testing & Validation

### Quick Testing Approach
- Use print statements to verify outputs during development
- For larger exercises, add simple test functions at the bottom of files:
```python
def test_my_function():
    assert my_function(input) == expected_output
    print("✓ Test passed")

if __name__ == "__main__":
    test_my_function()
```

## AI Agent Guidelines

- When adding new practice files, maintain the `practice*.py` naming convention
- Before suggesting major refactors, understand the learning goal of each exercise
- Preserve all code even after suggesting improvements—wrap suggestions in new functions to show alternatives
- Include time/space complexity analysis in algorithm solutions
- Add edge case tests for any utility functions
