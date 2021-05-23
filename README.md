# Test Performance Scenario

1. Where would be best to performance test for the site and what to encompass in the scripts?

	1. For initial tests I would wnat to test the site as close to the server as possible.  This would be to base line the perfomance by removing as many networking components as possible.  It should also be server side of any load balancing.  Eventually external facing connections should be used to to carry out load testing against.  The comparison between the "internal" and "external" tests will then give an idea of bottle necks in the sever components.
	2. The tests should script all user activity on the site. Each activity:
		* accessing home page,
		* site registration,  
		* going to Product Descrition Page, 
		* adding items to cart,
		* checkout process
2. What further questions would you have on the above statistics?
	* What sort of tests would be needed for this testing
		* peak usage
		* soak/endurance tests
		* load 
		* projected load
	* what are the expected breakdowns of site usage.  How many new accounts are created, how many users hit how many product pages before placing item in the the cart.  what are the cart checkout statistics (number of items, average cost etc.)
	* what rates of user introduction to the system is expected? 
	* what is the expected growth in the site usage so I can plan for the projected load test.
	