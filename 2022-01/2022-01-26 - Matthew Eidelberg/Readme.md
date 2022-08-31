# Matthew Eidelberg
#### stream date : 2022-Jan-26

## Who he is :
- Engineering Fellow at Optiv Inc
- Author of several Open-Source Tools and Frameworks
- Research focus - EDR, Evasion, and Bypasses
- Speaker at 
	- Defcon Red Team Village
	- Defcon Adversary Village
	- DerbyCon
	- BSides Las Vegas
	- GrrCon
	- RSA
(source : [Youtube ](https://www.youtube.com/watch?v=PfcDrhDlyUE))

### Social
[Youtube](https://www.youtube.com/results?search_query=Matthew+Eidelberg)<br>
[LinkedIN](https://www.linkedin.com/in/matthew-eidelberg-b0422997)<br>
[Twitter ](https://twitter.com/Tyl0us)<br>
<hr>
## Topic : AV, EDR evasion.

> - A trend in the last 2 years is the removing or unhooking of any type of telemetry from any time of security products.
	> - Userland hooking evasion
	> - Custom APIs to execute malicious code
	> - Removing hooks from process
	> - Diverting AMSI calls
	
A discussion ensued after this on the utility of detection alerts stemming from these activities contrasted with active efforts to thwart the unhooking activities. There is value on these activities because :-

> - Sometimes there is no analysis to follow up on those alerts ragarding where the execution is called from
> - Sometimes the alerts aren't followed up and can elist contradictory responses from SOC shift to another SOC shift.

Secondary C2s are important for those instances where an alert leads to the discovery and termination of the host of the primary C2

Deception techniques have their value however they are highly documented nowadays. They are not always key to success.

Misdirection is important in some engagements where deliberate loud activities could be initiated to direct attention away from the objective target.

Care must be taken not to cause an over-reaction to cause an operational impact where the entire environment is shutdown due to panic.


	

