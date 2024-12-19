# lab05


### 2
#### 2.2
![ภาพ](https://github.com/user-attachments/assets/f4842ecf-9aad-4f67-aa15-884a2b351a3a)

##### 2.3
```bash
cd .    # Stay in current directory
cd ..   # Move up one directory level
cd ~    # Go to home directory
cd /    # Go to root directory
```

### Command Explanations
- `cd .` - Remains in current directory (.)
- `cd ..` - Moves to parent directory
- `cd ~` - Returns to user's home directory
- `cd /` - Navigates to root directory
- `cd $` - Incorrect usage ($ requires environment variable)

#### 2.4
![ภาพ](https://github.com/user-attachments/assets/078d19a8-def4-441b-971f-fd0ca9972602)


### 3
#### 3.1 & 3.2
![ภาพ](https://github.com/user-attachments/assets/55f4dbd8-0d9f-4ad2-a2a3-437c45ea0c28)

#### 3.3
![ภาพ](https://github.com/user-attachments/assets/bab5354e-72ed-454f-ae0f-8c1e91131545)

```bash
ls      # Basic listing
ls -alt # Detailed listing with all files, sorted by time
```

The `-alt` flags provide:
- `-a`: Show hidden files
- `-l`: Long format with details
- `-t`: Sort by modification time

#### 3.4
![ภาพ](https://github.com/user-attachments/assets/585e89e4-ac76-4193-9e69-213439bcc0ee)

#### 3.5
![ภาพ](https://github.com/user-attachments/assets/2201266f-5625-45fd-a6eb-52f4f93f983d)

#### 3.7 - 3.10
![ภาพ](https://github.com/user-attachments/assets/15ec6c9f-c9bb-432b-a38c-408cbae5b616)

### 4
#### 4.1
![ภาพ](https://github.com/user-attachments/assets/557cc648-341f-4593-acf2-1563f1e946c8)
![ภาพ](https://github.com/user-attachments/assets/58406905-a1dd-4051-8cca-2491f2af3249)

#### 4.2
![ภาพ](https://github.com/user-attachments/assets/202ac8e5-3da9-4115-abd4-452b9b88ca2f)

#### 4.3
![ภาพ](https://github.com/user-attachments/assets/6d541fb2-9a3c-4fc6-b597-d3f2b8b1a0cf)

wc name.csv: Stands for "word count". It outputs:

    Number of lines,
    Number of words,
    Number of characters in the file.

#### 4.4
![ภาพ](https://github.com/user-attachments/assets/c8382bee-18ec-4d6e-992d-2955b2752323)

#### 4.5 

- `cat`: Display full content
- `more`: Paginated view
- `head`: First 10 lines
- `tail`: Last 10 lines
- `wc`: Count lines, words, and characters

### 5
#### 5.2
![ภาพ](https://github.com/user-attachments/assets/e6ab8de3-e9a7-4dc2-bab4-42334a6eb0db)

#### 5.3
![ภาพ](https://github.com/user-attachments/assets/f5ffed98-de91-444d-8bb0-a1929dea82ae)

#### 5.4 & 5.5
![ภาพ](https://github.com/user-attachments/assets/8b7c863d-57ca-499e-bb1b-adc1119e7de7)

### 6
#### 6.1
![ภาพ](https://github.com/user-attachments/assets/c37a1bc7-c511-4fce-8130-8553f630d384)

#### 6.2
![ภาพ](https://github.com/user-attachments/assets/dc1f6aa0-8c13-457b-a917-15cbb4f48091)

#### 6.3
![ภาพ](https://github.com/user-attachments/assets/cf7ae69d-36b4-45a1-8f5c-1cb22a3934b5)

- `ping`: Test network connectivity
  - Sends ICMP packets
  - Measures response time

![ภาพ](https://github.com/user-attachments/assets/369a65a4-685d-452c-8277-c234c241a9a4)

- `traceroute`: Track packet routes
  - Shows path to destination
  - Displays intermediate hops

#### 6.4 
- `netstat -n`: View active connections
  - Shows local and remote addresses
  - Displays connection states

![ภาพ](https://github.com/user-attachments/assets/f0ed4000-9a04-49db-bb70-6088f91feb0f)

Displays active network connections with numerical addresses and port numbers.
The table includes:

    Local Address: Your system's IP and port.
    Foreign Address: Remote system's IP and port.
    State: Connection state (e.g., ESTABLISHED, LISTEN, CLOSE_WAIT).

### 7
#### 7.1
![ภาพ](https://github.com/user-attachments/assets/69b70348-fde3-4417-99c4-9cea208601ff)

- Real-time system process monitor
- Shows:
  - CPU usage
  - Memory usage
  - System uptime

#### 7.2 
![ภาพ](https://github.com/user-attachments/assets/3a4c42f5-54a6-4df1-b442-f19e09558f44)

Enhanced system monitor with:
- Color-coded interface
- Easy process management
- Customizable display
- Scrollable process list
