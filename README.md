# Experiment 4: Berkeley Clock Synchronization Algorithm

### 1. Commands to Run
Open your terminal in this directory and execute:
```bash
javac BerkeleyAlgorithm.java
java BerkeleyAlgorithm
```

---

### 2. Input Sequence
1. **Master Time:** Enter time in `HH:mm:ss` format (e.g., `03:00:00`).
2. **Number of Slaves:** Enter total slave nodes (e.g., `2`).
3. **Slave Times:** Enter time in `HH:mm:ss` for each slave node.

---

### 3. Example Execution & Output

```
=== Berkeley Clock Synchronization Algorithm ===
Enter Master node's initial time (HH:mm:ss): 0c
Enter the number of slave nodes: 2
Enter time for Slave 1 (HH:mm:ss): 03:15:00
Enter time for Slave 2 (HH:mm:ss): 03:45:00

----------------- Synchronization Results -----------------
Average time difference adjustment: 1200 seconds
Synchronized System Time: 03:20:00
-----------------------------------------------------------
Master Node Adjustment: 1200s -> Synchronized: 03:20:00
Slave 1 Offset: 300s -> Synchronized: 03:20:00
Slave 2 Offset: -1500s -> Synchronized: 03:20:00
```
