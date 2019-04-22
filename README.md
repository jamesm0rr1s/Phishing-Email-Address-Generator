# Phishing Email Address Generator (PhishGen)

PhishGen is a penetration testing and red teaming tool that automates the process of generating email addresses using names scraped from social media sites and scrapes email addresses from additional websites. This script was tested with Python 2.7

## Main Features

 - A domain and company to search for will need to be provided
 - The format of the email addess can be provided or guessed by scraping a website
 - The LinkedIn company ID can be provided or guessed by scraping a website
 - Profiles will be searched for
 - Additional profiles will be searched for using common first names, last names, job titles, and certifications
 - Additional websites will be scraped for email addresses
 - The results will be saved to a csv file

## Installation

Clone the GitHub repository
```
git clone https://github.com/jamesm0rr1s/Phishing-Email-Address-Generator /opt/jamesm0rr1s/Phishing-Email-Address-Generator
```

## Requirements

 - A LinkedIn account
   - Connections with multiple employees. (The more the better)
 - The script will attempt to install the following requirements if they are not already installed. The following commands can be used to manually install the requirements:
```
pip install beautifulsoup4
pip install colorama
```

## Usage

Generate email addresses by running the following command:
```
python /opt/jamesm0rr1s/Phishing-Email-Address-Generator/PhishGen.py
```

## Example Screenshots

Example of Usage (Screenshot Shortened)  
![ExampleOfUsage](screenshot1.png?raw=true "ExampleOfUsage")

Example of Output (Screenshot Shortened)  
![ExampleOfOutput](screenshot2.png?raw=true "ExampleOfOutput")
