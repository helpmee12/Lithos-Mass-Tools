# Lithos Mass Tools

Lithos Mass Tools is a collection of Python scripts for various automated tasks, including username checking, generation, password strength checking, and webhook testing.

## Features

- **Username Checker**: Checks the availability of usernames on Roblox using asyncio and aiohttp.
- **Username Generator**: Generates random usernames of specified lengths.
- **Password Strength Checker**: Evaluates the strength of passwords based on length.
- **Webhook Tester**: Sends test messages to webhooks for verification.

## Requirements

- Python 3.7+
- aiohttp
- tqdm
- colorama

## Setup

1. **Installation**:
   - Clone the repository: `git clone https://github.com/your/repository.git`
   - Install dependencies: `pip install -r requirements.txt`

2. **Configuration**:
   - Edit `main.py` to set your preferred webhook URL (`webhook_url = "https://your-webhook-url-here"`).

3. **Usage**:
   - Run `main.py` and follow the on-screen prompts to choose a tool:
     ```bash
     python main.py
     ```

## Usage Examples

### Checking Usernames

```python
from main import open_username_checker

open_username_checker()
