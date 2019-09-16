---
title: "Python environments"
description: "Manage python dependencies per project"
author:
  name: "Petar Stoyanov"
  desc: " "
date: 2019-08-28
draft: false
categories:
- Python
- Dependencies
---

# Install package for virtual environment support

```
python -m pip install virtualenv
```

```
python -m virtualenv env
```

// in folder with env
```
source ./env/Scripts/activate
```

which python = should be path to project folder, not system wide

```
python -m pip freeze > requirements.txt
```

```
python -m pip install -r requirements.txt
```
