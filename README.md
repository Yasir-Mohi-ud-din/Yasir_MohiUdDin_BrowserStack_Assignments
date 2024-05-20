# BrowserStack Assignments

### Create virtual environment
```bash
python3 -m venv venv
```

### Activate Virtual Environment:
```bash 
source venv/bin/activate
```

### Install Dependencies:
```bash 
pip install -r requirements.txt
```

### Set BrowserStack Credentials:
```bash
export BROWSERSTACK_USERNAME=<your_username>
export BROWSERSTACK_ACCESS_KEY=<your_access_key>
```

### Local Test Execution:
```bash
python3 assignment.py
```

### Configuration for GitHub Actions:
create Github Secrets for BROWSERSTACK_USERNAME and BROWSERSTACK_ACCESS_KEY

