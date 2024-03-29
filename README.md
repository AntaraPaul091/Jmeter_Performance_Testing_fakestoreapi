Dear,

I’ve completed performance test on frequently used API for test App https://fakestoreapi.com.
Test executed for the below mentioned scenario in server https://fakestoreapi.com.

10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 4.4 And Total Concurrent API requested: 290.

50 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 23 And Total Concurrent API requested: 1450.

100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 35 And Total Concurrent API requested: 2900.

 While executed 100 concurrent request, found 1 request got connection timeout and error rate is 0.03%.
 
 Summary: Server can handle almost concurrent 2850 API call with almost zero (0) error rate.
 Report Image:
 ![report_img](https://github.com/AntaraPaul091/Jmeter_Performance_Testing_fakestoreapi/assets/66947824/4ccc00e5-e33f-4db6-adbe-c6ee2fb3295b)
