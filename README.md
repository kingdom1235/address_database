# Address_database

![Language](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

#### Video Demo: https://www.youtube.com/watch?v=tC6hV7XJhJM&t=46s&ab_channel=Kh%E1%BA%A3iTr%E1%BA%A7n

#### Description: An address database script to save people's information using SQLite3.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Bash**: The Bourne Again SHell, a command language interpreter.
- **SQLite3**: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.

You can install these using the following commands on Debian-based systems:

```bash
sudo apt update
sudo apt install -y bash sqlite3
```

## Installation

Follow these steps to install the Quote and To-Do Manager

1. Clone the repository:
```bash
git clone https://github.com/kingdom1235/address_database.git
cd address_database
```

2. Run the installation script:
```bash
./install.sh
```

## Usage

You can use the address_database script to manage people's information
```bash
Usage: address_database
```
Main menu with feature choose menu state (Add, Search, Edit)
```bash
My Database Project
Please choose the below options:

1. Add Entry
2. Search / Edit Entry
3. Show log file
x. Exit

Note: Script Timeout is set
Please choose your option:
```

Add entry menu with feature add people's information to address database.
```bash
My Database Project
Please choose the below options:

Add New Entry Screen:

1. Name                 :
2. Email                :
3. Tel No               :
4. Mob No               :
5. Place                :
6. Message              :
7. Save
x. Exit
Please choose the field to be added:
```

Search menu with feature search people's information from address database and choose to delete or edit it.
```bash
My Database Project
Please choose the below options:

Search / Edit by:

1. Name                 :
2. Email                :
3. Tel No               :
4. Mob No               :
5. Place                :
6. Message              :
7. All
x. Exit
Please choose the field to be searched:
```

Edit menu with feature edit people's information in address database.
```bash
My Database Project
Please choose the below options:

Search / Edit by:

1. Name                 :
2. Email                :
3. Tel No               :
4. Mob No               :
5. Place                :
6. Message              :
7. Save
x. Exit
Please choose your option:
```

And finally show log file with feature show every action on address database

## This was CS50!
