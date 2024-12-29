# SMS Call Bomber

**Disclaimer:**
> SMS Bomber, aka BombitUP is created for educational purposes only. Misusing this tool to harm others, disrupt services, or invade privacy is illegal and unethical.

Always use this responsibly and with proper consent. The developers are not responsible for any misuse of this tool.

For people with little to no knowledge, access the live version here: https://bombit.app

## Overview

SMS Call Bomber is a command-line tool designed to send a large number of SMS or initiate repeated call requests to a specified phone number. It is built for testing and educational purposes, such as stress testing APIs or demonstrating vulnerabilities in communication systems.

## How SMS Call Bomber Works?

1. **Input Target Details**: The user provides a target phone number and optional configuration parameters.
2. **Send Requests**: The tool utilizes publicly available APIs or communication gateways to send SMS or call requests.
3. **Customization**: Users can set the number of messages or calls and the delay between them to simulate various scenarios.

**Important:** The tool does not use illegal methods to send messages or make calls. It works by interacting with services that allow public communication requests. Unauthorized use is prohibited.

## Features

- **Customizable Parameters**:
  - Number of SMS or calls to send.
  - Delay between requests.
- **Platform Compatibility**:
  - Works on Linux, macOS, and Windows.
- **Simple CLI**:
  - User-friendly and straightforward interface.

## Prerequisites

- **Python**: Version 3.7 or higher.
- **Required Modules**: Install dependencies listed in `requirements.txt`.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sms-call-bomber.git
    cd sms-call-bomber
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python sms_bomber.py
    ```

2. Follow the prompts to:
    - Enter the target phone number.
    - Specify the number of SMS or calls.
    - Set a delay (optional).

3. Confirm the configuration to start the process.

**Demo:**

Here’s an example interaction:

```text
Target Number: +1234567890
Number of Messages: 50
Delay Between Messages (seconds): 1
Starting bombardment...
[1/50] Message sent successfully
[2/50] Message sent successfully
...
```

## Use Cases

- **Security Testing**: Simulate high-volume message traffic to identify vulnerabilities in communication systems.
- **API Stress Testing**: Test the robustness of SMS or call handling APIs.

## Warning

Using this tool without proper authorization or consent is illegal. Ensure you have explicit permission from the target recipient or system owner before proceeding.

## Contributing

Contributions to improve this tool are welcome. Here’s how you can help:

1. Fork the repository.
2. Create a new branch for your feature or bug fix (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push your branch to GitHub (`git push origin feature-name`).
5. Submit a pull request.

## License

This project is licensed under the MIT License

---

**Acknowledgment:** This tool is inspired by similar projects like BombitUP. However, this tool is independently developed for educational and ethical purposes.


