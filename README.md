# Phone Number Info Lookup
A simple Python tool that uses the `phonenumbers` library to validate and retrieve information about a phone number such as:
- Region/Time zone
- Service provider
- Country/Geolocation
---

## Features
- Validates international phone numbers
- Displays region and time zone
- Shows telecom carrier/service provider
- Displays country and city info
---

## Requirements
- Python 3.x
- `phonenumbers` module
---

## Install dependencies using:
```bash
pip install phonenumbers
```
---

## Usage
1. Run the script in the terminal:
```bash
python phone_number_info.py
```
2. You'll be prompted to enter a phone number in international format:
```bash
Enter Phone number with country code(+xx xxxxxxxxx): +92 3001234567
```
3. Example output:
```bash
Phone Number belongs to region : ('Asia/Karachi',)
Service Provider :  Jazz
Phone number belongs to country :  Pakistan
```
---

## Contributing
Feel free to open issues or submit pull requests if you want to contribute to this project. I welcome any contributions and suggestions to improve this.

---

## Contact
For questions or feedback, contact: abideen5036@gmail.com

---

