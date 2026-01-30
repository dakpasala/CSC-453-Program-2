Developers: Dakshesh Pasala, Ivan Alvarez

Question: What happens to response time with RR as quantum lengths increase? 
Answer: As the quantum increases, RR starts to behave like FCFS and the average response time increases. This is because processes, not including the first, have to wait longer before getting any CPU time. The issue is if we were to reduce the quantum time, the response time will improve, but context switching overhead will increase.