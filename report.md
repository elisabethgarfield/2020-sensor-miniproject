Elisabeth Garfield & Patricia Ganchozo
EC 463 Senior Design Mini Project Report
September 17 2020

  For EC 463 Senior Design, Patricia and I were asked to program a system to report and find average temperatures based on a set of simulated sensors provided by the 
staff. Using Python websockets libraries, as opposed to a compiled language like C++ websockets, increased the difficulty of this miniproject as Patricia and I are 
relatively unfamiliar with Python and more comfortable with a C++ library. It would be preferable for the server to poll the sensors rather than have the senors reach 
out to the server when they have data so that the burden lays on the server rather than the sensors. A minor disadvantage to this method could be that if the server
were to go down, none of the sensors would report data, while if a sensor goes down, the server would still receive data. This disadvantage goes either way with both methods. 

  The most similar instance of this simulation and its stated requirements is, in our minds, a Nest Home type operation. This could also be applied to larger settings, 
including weather mapping over fields to determine prime locations for different types of crops. However, this simulation is deficient in that it does not account for 
humidity, air quality, light exposure, UV ratings, or other qualities that could affect the "feel" or effective temperature in the room. 

how is this simulation reflective of the real world?
how is this simulation deficient? What factors does it fail to account for?
how is the difficulty of initially using this Python websockets library as compared to a compiled language e.g. C++ websockets
would it be better to have the server poll the sensors, or the sensors reach out to the server when they have data?
