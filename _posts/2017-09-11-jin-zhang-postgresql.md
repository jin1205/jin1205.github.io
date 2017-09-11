---
layout: post
title: "PostgreSQL Setup"
date: 2017-09-11
---
### Install PostgreSQL
```bash
brew update && brew install postgresql
```

### To have launchd start postgresql at login:
```bash
brew services start postgresql
```

### To solve: psql command not found
```bash
export PATH=/Library/PostgreSQL/9.6/bin:$PATH
```

### For the database viewer, use postico


psql -d super_awesome_application -U postgres
 
psql glimpse_pilot < /Users/ux/Downloads/dev_glimpse.sql -U postgres
