# Project 9 – Splunk Search Processing Language (SPL) Fundamentals

## Overview

In this project, I learned the fundamentals of Splunk Search Processing Language (SPL) by performing searches against security logs stored in my SOC Lab index. The objective was to understand how to retrieve, filter, organize, and summarize security events using the most common SPL commands used by SOC analysts.

---

## Objective

- Learn the fundamentals of Splunk Search Processing Language (SPL).
- Search all indexed events.
- Search by index, host, and source.
- Organize search results using SPL commands.
- Analyze and summarize log data to simulate real SOC investigations.

---

## Lab Environment

- Windows 11
- Splunk Enterprise 10.4.1
- Splunk Web
- SOC Lab Index (soc_lab)
- Sample Security Logs

---

## Skills Practiced

- Search Processing Language (SPL)
- Searching by Index
- Searching by Host
- Searching by Source
- Data Organization
- Event Analysis
- Security Log Investigation
- SIEM Navigation

---

## Tools Used

- Splunk Enterprise
- Windows 11
- GitHub

---

## SPL Commands Learned

| Command | Purpose |
|----------|----------|
| `index=soc_lab` | Search events within the SOC Lab index |
| `host=FrancisHP` | Filter events by host |
| `source=auth.log` | Search a specific log source |
| `table` | Display selected fields in a table |
| `stats count by source` | Count events grouped by source |
| `sort -count` | Sort results from highest to lowest |
| `head` | Display the first events |
| `tail` | Display the last events |
| `dedup` | Remove duplicate values |

---

## Lab Activities

- Accessed the Search & Reporting application.
- Executed the first SPL search.
- Queried events using the SOC Lab index.
- Filtered data by host.
- Filtered data by source.
- Displayed selected fields using the table command.
- Counted events using the stats command.
- Sorted results using the sort command.
- Displayed the first and last events using head and tail.
- Removed duplicate events using dedup.

---

# Screenshots

### 01 – Search and Reporting App

![01 Search and Reporting App](01%20Search%20and%20Reporting%20App.png)

---

### 02 – Search All Events

![02 Search All Events](02%20Search%20All%20Events.png)

---

### 03 – Search Results - All Events

![03 Search Results - All Events](03%20Search%20Results%20-%20All%20Events.png)

---

### 04 – Search by Index

![04 Search by Index](04%20Search%20by%20Index.png)

---

### 05 – Search by Host

![05 Search by Host](05%20Search%20by%20Host.png)

---

### 06 – Search by Source

![06 Search by Source](06%20Search%20by%20Source.png)

---

### 07 – Table Command

![07 Table Command](07%20Table%20Command.png)

---



### 09 – Sort Command

![09 Sort Command](09%20Sort%20Command.png)

---

### 10 – Head Command

![10 Head Command](10%20Head%20Command.png)

---

### 11 – Tail Command

![11 Tail Command](11%20Tail%20Command.png)

---

### 12 – Dedup Command

![12 Dedup Command](12%20Dedup%20Command.png)

---

## Lessons Learned

- Learned how Splunk searches indexed security data.
- Gained experience using Search Processing Language (SPL).
- Understood the relationship between indexes, hosts, and sources.
- Learned how to organize search results using the table command.
- Used statistical commands to summarize log data.
- Practiced sorting and filtering security events.
- Learned how to remove duplicate results to simplify investigations.

---

## SOC Analyst Takeaways

Search Processing Language (SPL) is the primary language used by SOC analysts to investigate security events within Splunk. Understanding how to search, filter, organize, and summarize log data allows analysts to quickly identify suspicious activity, reduce investigation time, and improve incident response. These foundational SPL commands serve as the building blocks for more advanced threat hunting and security investigations.
