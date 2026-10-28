TC-001: Manual Baseline Analysis

## Objective

Establish a baseline for the time required to identify high-priority security events without automated prioritization.

## Procedure

Synthetic security logs were generated and ingested into Elasticsearch using Filebeat. A dataset of 1,000 logs was reviewed manually through Kibana without automated priority classification.

## Results

- **Logs analyzed: 1,000
- **Experimental runs: 5
- **Average identification time: 3,144 seconds (52.4 minutes)
- **Median time: 3,120 seconds
- **Standard deviation: 201.69 seconds

## Conclusion

Manual analysis required significantly more time to identify high-priority events and established the baseline for comparison with the automated prioritization system.
