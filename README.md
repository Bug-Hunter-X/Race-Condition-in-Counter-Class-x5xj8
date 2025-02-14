This repository contains a simple Java program that demonstrates a race condition. The program uses two threads to increment a counter variable. Due to the lack of synchronization, the final count may be less than the expected value of 20000. The solution demonstrates how to fix this issue by using the synchronized keyword.