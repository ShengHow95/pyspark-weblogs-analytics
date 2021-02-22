# Simple Web Logs Analytics with PySpark

Metadata for .log file
timestamp, clientIP, backendIP, request_processing_time, backend_processing_time, response_process_time, status_code, backend_status_code, received_bytes, sent_bytes, request, user_agent, ssl_cipher, ssl_protocol

The .log file is using the same format as standard Dump from Amazon Elastic Load Balancing. 

More information can be found here
https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/access-log-collection.html

### Use Cases:
1. Aggregate the pages by clientIP during a session.
2. Find average session time. 
3. Find unique URL visits per session. 
4. Find IPs with the longest session times