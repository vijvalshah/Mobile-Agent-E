# Mobile-Agent-E

Mobile-Agent-E is a hierarchical multi-agent framework capable of self-evolution through past experiences for mobile device automation.

## Features

- Hierarchical multi-agent architecture
- Self-evolution through experience
- Complex task handling
- Multi-app interaction support
- Visual perception and action execution

## Installation

1. Clone the repository:
```bash
git clone https://github.com/vijvalshah/Mobile-Agent-E.git
cd Mobile-Agent-E
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
# Create a .env file with your API keys
OPENAI_API_KEY=your_openai_key
GEMINI_API_KEY=your_gemini_key
CLAUDE_API_KEY=your_claude_key
QWEN_API_KEY=your_qwen_key
```

## Usage

1. Connect your Android device via ADB
2. Run the agent:
```bash
python inference_agent_E.py
```

## Project Structure

- `MobileAgentE/`: Core agent components
  - `agents.py`: Agent classes and logic
  - `api.py`: API communication
  - `controller.py`: Device control
  - `text_localization.py`: Text detection
  - `icon_localization.py`: Icon detection
  - `crop.py`: Image processing
- `inference_agent_E.py`: Main execution script

## License

MIT License

Copyright (c) 2024 Vijval Shah

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.