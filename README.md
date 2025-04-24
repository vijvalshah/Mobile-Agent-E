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
git clone https://github.com/yourusername/Mobile-Agent-E.git
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

This project is licensed under the MIT License - see the LICENSE file for details.

## Citation

If you use this code in your research, please cite:
```
@article{wang2024mobile,
  title={Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks},
  author={Wang, Zhenhailong and Xu, Haiyang and Wang, Junyang and Zhang, Xi and Yan, Ming and Zhang, Ji and Huang, Fei and Ji, Heng},
  journal={arXiv preprint arXiv:2501.11733},
  year={2024}
}
```