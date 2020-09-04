Bandit tweaked for personal use. The "calls.py" file is updated with new rulesets that find vulnerabilities in django and flask

# Setup process
For Python 2.7 - 
1. pip install bandit 
2. Navigate to C:\Python27\Lib\site-packages\bandit\blacklists\
3. Replace existing calls.py with calls.py downloaded from this repo
4. Run as usual, that's it.

For Python 3.x - 
1. pip3 install bandit
2. Navigate to C:\Users\username\AppData\Local\Programs\Python\Python38\Lib\site-packages\bandit\blacklists\
3. Replace existing calls.py with calls.py downloaded from this repo
4. Run as usual, that's it.

Tedious, yes! But works. 
