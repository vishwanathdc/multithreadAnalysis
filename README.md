# multithreadAnalysis
1. This project is to analyze multithreading concept and throughput.
2. Throughput is defined here as the number of requests served per second.
3. A multithreaded http server word count application is developed.
4. The word count application responds with word count for a given search query word.
5. Jmeter test plan is used to check throughput.
6. Throughput increases and reaches maximum of ~1500 requests/sec till number of threads in threadpool equals virtual cores and remains constant with increase in threads.
