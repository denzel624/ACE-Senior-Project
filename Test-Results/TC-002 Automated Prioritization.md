# TC-002: Automated Contextual Prioritization

## Objective

Evaluate whether automated contextual scoring could reduce the time required to identify high-priority security events.

## Procedure

Synthetic security logs were processed through Filebeat and Elasticsearch. A Kibana runtime field applied weighted scoring rules based on severity indicators, account information, and network context. Events were classified as HIGH, MEDIUM, or LOW priority.

## Results

- **Logs analyzed:** 1,065
- **Experimental runs:** 5
- **Average identification time:** 6.8 seconds
- **Median time:** 6 seconds
- **Standard deviation:** 1.92 seconds
- **Reported classification accuracy:** 100% within the controlled synthetic test
- **High-priority alerts reviewed:** 10-15 

## Conclusion

Automated contextual prioritization substantially reduced identification time compared with manual analysis. The results demonstrated the effectiveness of rule-based scoring within the controlled testbed.
