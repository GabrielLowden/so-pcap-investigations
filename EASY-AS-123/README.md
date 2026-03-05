# Case Created

![Open_Case](../EASY-AS-123/screenshots/case.png)

- Quick note the IP = 45.131.214.85:443
    - signature hits triggered for NetSupport Man. RAT

## First Look

![elastic_log_ingestion](/EASY-AS-123/screenshots/init-log-ingestion.png)

- Filter by dates stated in problem (Feb 28, 2026)
- 3,152 Logs generated
- Zeek and suricata
- All data is network related

## Go to hunt

![hunt_filtered](/EASY-AS-123/screenshots/filter-hunt.png)

- Filter by dates again
- grpu
