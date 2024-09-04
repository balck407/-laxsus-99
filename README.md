# Navigate to your script directory
cd ~/scripts

### 4. **Create a Setup Script (Optional)**

You can also create a `setup.py` file for easier installation. This allows users to install dependencies automatically. Here’s an example setup script:

```python
from setuptools import setup

setup(
    name='laxsus-99',
    version='0.1',
    py_modules=['laxsus_99'],
    install_requires=[
        'requests',
    ],
    entry_points={
        'console_scripts': [
            'laxsus-99=laxsus_99:main',
        ],
    },
)



# Initialize git repository if not done already
git init

# Add remote repository
git remote add origin https://github.com/yourusername/laxsus-99.git

# Add files to the repository
git add laxsus-99.py
git add README.md

# Commit the files
git commit -m "Initial commit"

# Push files to GitHub

 Write Installation Instructions







1
sudo apt update
sudo apt install python3 python3-pip

2
pip3 install requests

3
python3 laxsus-99.py
