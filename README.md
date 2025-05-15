# Refashion

## Description
A Smart Mirror that incorporates features for fashion capture, clothing categorization, and seamless integration with a dedicated mobile app.

## Setup

### Environment Variables
This project uses environment variables to manage API keys and sensitive information. Create a `.env` file in the root directory with the following variables:

```env
# Hugging Face API Token for clothing classification
HUGGINGFACE_TOKEN=your_huggingface_token_here

# Add other API keys as needed
# OPENAI_API_KEY=your_openai_key_here
# OTHER_API_KEY=your_other_key_here
```

To get your Hugging Face API token:
1. Create an account at [Hugging Face](https://huggingface.co)
2. Go to your profile settings
3. Navigate to "Access Tokens"
4. Create a new token with appropriate permissions

### Installation
1. Clone the repository
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create the `.env` file as described above
5. Run the application

## Contributing
Don't commit to main. When you want to implement a new feature, create a new feature branch from the branch-folder (app, server, or mirror) and name the branch "[feature-name]-feature".

### Security Notes
- Never commit API keys or sensitive information directly in the code
- Always use environment variables for sensitive data
- The `.env` file is gitignored and should not be committed
- If you accidentally commit sensitive information, contact the maintainers immediately

## Authors and Acknowledgment
Anindya Barua, Olivia Chan, Kevin Ge, Nathan Martin, Ryan Nguyen, Eric Zhang
