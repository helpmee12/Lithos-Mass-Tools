# Roblox Toolset

This is a Python toolset for interacting with Roblox, including functionalities for checking username availability and displaying moderation data.

## Features

1. **Username Availability Checker**: Check the availability of Roblox usernames within a specified length range and optionally match a given pattern.
2. **Display Not Approved Data**: Display moderation data for a given `.ROBLOSECURITY` and `.RBXIDCHECK` cookie.
3. **Concurrent Username Checks**: Improve performance by checking multiple usernames concurrently.
4. **Configuration File**: Load configurable parameters from a `config.yaml` file.

## Requirements

- Python 3.6+
- `aiohttp`
- `colorama`
- `requests`
- `tqdm`
- `pyyaml`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/roblox-toolset.git
    cd roblox-toolset
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Create a `config.yaml` file in the root directory with your webhook URL:
    ```yaml
    webhook_url: "your_webhook_url_here"
    ```

## Usage

1. Run the script:
    ```sh
    python main.py
    ```

2. Follow the on-screen prompts:
    - **1. Username Availability Checker**: 
        - Enter the minimum and maximum username length.
        - Enter the number of usernames to check per length.
        - Optionally, enter a username pattern to match.
    - **2. Display Not Approved Data**:
        - Enter your `.ROBLOSECURITY` and `.RBXIDCHECK` cookies.
    - **3. Exit**: 
        - Exit the tool.

## Example `config.yaml`

```yaml
webhook_url: "your_webhook_url_here"
