# Stratus: cost-aware container scheduling in the public cloud
Stratus: cost-aware container scheduling in the public cloud [https://www.pdl.cmu.edu/PDL-FTP/CloudComputing/p121-Chung.pdf](https://www.pdl.cmu.edu/PDL-FTP/CloudComputing/p121-Chung.pdf)

Pretty incredible paper at what it does. Showcases the performance impact with cost benefits for their packing (batching) algorithm for cloud tasks, as well as for other solutions. Really well made, and ready to include in performance/gains forecasts/powerpoints.

Overall the paper led to a lot of assorted thoughts. 
Batching tasks that aren't incredibly urgent seems powerful for cost (and emissions) savings.
Fog/Edge clouds seem great for local non-peak computing and offloading stresses to the cloud. Per there being more traffic, it shouldn't take long to find a matching for batching in those cases. 
Greedy approaches seem to be pretty good for packing. Just have two scores, size and importance. Take the highest importance that size allows. Increment importance as time goes on. 
Proper estimates for resource consumption seem important for packing. 
