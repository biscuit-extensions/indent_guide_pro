# Indent_guide_pro

Enhanced indentation guides and block scope visualizers

## 🔧 Development

### Customizing the Extension

1. **Main Extension Logic**: Edit `src/indent_guide_pro/extension.py`
2. **Entry Point**: Modify `src/indent_guide_pro/__init__.py` if needed
3. **Tests**: Update `tests/test_indent_guide_pro.py` to match your changes

### Adding New Functionality

- **`src/indent_guide_pro/extension.py`**: Contains the main `greet()` function and extension logic
- **`tests/test_indent_guide_pro.py`**: Add tests for your new functionality

## Running the Development Server

To run the development server, use the following command:

```bash
biscuit ext dev
```

This will start the server and allow you to test your extension in a local environment.

### Testing

Make sure to install `pytest` before running the tests.

```bash
biscuit ext test
```

Modify tests to reflect the changes you made to the extension.

## Publishing & Updating

To publish or update your extension, use the following commands, and follow the instructions provided by the Biscuit CLI:

```bash
biscuit ext publish
biscuit ext update
```

### Project Structure

```
indent_guide_pro/
├── src/
│   └── indent_guide_pro/
│       ├── __init__.py          # Extension entry point
│       └── extension.py         # Main extension logic
├── tests/
│   ├── __init__.py
│   ├── conftest.py             # Pytest configuration
│   └── test_indent_guide_pro.py
├── pyproject.toml              # Project configuration
└── README.md                   # This file
```

---

**Author**: billyeatcookies  
**Version**: 0.1.0
