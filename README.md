# Offline Ansible Installation

## Download the Dependencies

```
pip wheel -r requirements.txt --wheels-dir=./wheels
```

## Install Ansible in Offline mode

```
pip install -r requirements.txt --find-links=./wheels --no-index
```
