18:18 22112024

<Information> Application: Available RAM: 32.00 GiB; logical cores: 20; used cores: 8.


# docker run -it --rm --memory="8192m" --cpus="2" -p 9000:9000 clickhouse:24.8.7.41

127.0.0.1:9000, queries: 5289, QPS: 8.747, RPS: 6703199.109, MiB/s: 484.013, result RPS: 48.116, result MiB/s: 0.004.

0.000%		0.802 sec.	
10.000%		2.601 sec.	
20.000%		3.300 sec.	
30.000%		3.806 sec.	
40.000%		4.695 sec.	
50.000%		6.498 sec.	
60.000%		8.206 sec.	
70.000%		9.102 sec.	
80.000%		9.904 sec.	
90.000%		10.808 sec.	
95.000%		11.599 sec.	
99.000%		12.893 sec.	
99.900%		14.594 sec.	
99.990%		14.902 sec.

------
--max_threads=2

# docker run -d --rm --memory="32768m" --cpus="8" -p 9000:9000 clickhouse:24.8.7.41

<Information> Application: Available RAM: 32.00 GiB; logical cores: 20; used cores: 8.

Queries executed: 21656 (1082800.000%).

127.0.0.1:9000, queries: 21656, QPS: 36.019, RPS: 27598270.334, MiB/s: 1990.710, result RPS: 198.105, result MiB/s: 0.016.

0.000%		0.081 sec.	
10.000%		0.601 sec.	
20.000%		0.792 sec.	
30.000%		0.982 sec.	
40.000%		1.200 sec.	
50.000%		1.597 sec.	
60.000%		1.902 sec.	
70.000%		2.115 sec.	
80.000%		2.322 sec.	
90.000%		2.605 sec.	
95.000%		2.811 sec.	
99.000%		3.222 sec.	
99.900%		3.709 sec.	
99.990%		4.113 sec.

# docker run -d --rm --memory="63488m" --cpus="20" -p 9000:9000 clickhouse:24.8.7.41


Queries executed: 42862 (2143100.000%).

127.0.0.1:9000, queries: 42862, QPS: 71.401, RPS: 54708419.244, MiB/s: 3950.288, result RPS: 392.707, result MiB/s: 0.031.

0.000%		0.024 sec.	
10.000%		0.327 sec.	
20.000%		0.441 sec.	
30.000%		0.564 sec.	
40.000%		0.689 sec.	
50.000%		0.812 sec.	
60.000%		0.923 sec.	
70.000%		1.034 sec.	
80.000%		1.161 sec.	
90.000%		1.337 sec.	
95.000%		1.486 sec.	
99.000%		1.780 sec.	
99.900%		2.177 sec.	
99.990%		2.466 sec.


# NATIVE

Queries executed: 42828 (2141400.000%).

127.0.0.1:9000, queries: 42828, QPS: 71.328, RPS: 54652352.754, MiB/s: 3946.240, result RPS: 392.305, result MiB/s: 0.031.

0.000%		0.020 sec.	
10.000%		0.314 sec.	
20.000%		0.426 sec.	
30.000%		0.549 sec.	
40.000%		0.679 sec.	
50.000%		0.811 sec.	
60.000%		0.930 sec.	
70.000%		1.045 sec.	
80.000%		1.173 sec.	
90.000%		1.350 sec.	
95.000%		1.501 sec.	
99.000%		1.806 sec.	
99.900%		2.162 sec.	
99.990%		2.478 sec.	
