# HTTP Log Analysis Using Splunk SIEM

## Introduction
HTTP (Hypertext Transfer Protocol) logs provide detailed information about web traffic, including client requests, server responses, and user behavior. These logs are critical for monitoring, troubleshooting, and detecting potential security threats.

This project focuses on analyzing HTTP log data using Splunk SIEM to identify patterns, detect anomalies, and perform basic threat hunting.

## Objectives
- Ingest HTTP log data into Splunk
- Extract and analyze important fields
- Understand web traffic behavior
- Detect anomalies and suspicious activity
- Document findings in a structured report

## Project Structure
HTTP-Splunk-Analysis/
\u2502
\u251c\u2500\u2500 README.md
\u251c\u2500\u2500 data/
\u251c\u2500\u2500 screenshots/
\u251c\u2500\u2500 queries/
\u2502 \u2514\u2500\u2500 splunk_queries.txt
\u2514\u2500\u2500 report/
\u2514\u2500\u2500 analysis_report.md


## Data Source
Sample HTTP log data is used for analysis. The dataset contains HTTP requests, response codes, URLs, and user-agent information.

## Tools Used
- Splunk SIEM
- HTTP log dataset

## Methodology
1. Upload HTTP logs into Splunk
2. Extract relevant fields such as method, URI, status, and IPs
3. Run SPL queries to analyze traffic patterns
4. Identify anomalies and suspicious behavior
5. Document findings in the report

## Status
Project initialized. Data ingestion and analysis in progress.
