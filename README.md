
# Formative One - Regex Onboarding Hackathon

This project demonstrates the use of Python and regular expressions (`re`) to extract structured data from unstructured text.

## 🔍 Features

The script can extract the following from a large block of text:

* 📧 **Email addresses**
* 🌐 **URLs**
* 🏷️ **HTML tags**
* 🏷️ **Hashtags**
* 💰 **Currency amounts (USD)**

## 📁 File Structure

```
main.py          # Contains all extractors and sample data
README.md        # You're reading it :)
```

## 🧰 Requirements

* Python 3.7+

## 🚀 Running the Script

Clone the repository and run the Python file:

```bash
python main.py
```

You'll see categorized output printed in your terminal.

## 🧪 Sample Output

Example data is embedded directly in the script (`SAMPLE_TEXT`) and used to demonstrate each extractor.

```bash
============
Emails
============
- info@openai.com
- john.doe@company.co.uk
- finance@biz.org
- support@service.net
- first.last@uni.edu
============

============
URLs
============
- https://www.openai.com
- https://blog.openai.com/post?id=123.
- https://partner1.example.org/page?id=456
- http://partner2.net.
- https://forum.techcommunity.org/topic?id=ai-tools.
============

============
HTML Tags
============
- <p>
- </p>
- <div class="container">
- <img src="banner.jpg" alt="Sale Banner">
- </div>
- <div>
- <p>
- </div>
============

============
Hash Tags(#)
============
- #OpenAI
- #ArtificialIntelligence
- #ThisIsAHashtag
============

============
Currencies($)
============
- $19.99
- $1,234.56
- $0.99
============
```

## 🧠 Notes

* Regex patterns are well-documented in code comments.
* This is not a full HTML or URL parser—best suited for light extraction tasks.
* Edge cases are handled where applicable (e.g., invalid hashtags, malformed emails).
