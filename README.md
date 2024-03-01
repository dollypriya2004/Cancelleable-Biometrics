# Cancelleable-Biometrics

Understanding and Implementing Cancellable Templates in Biometrics for privacy protection

Implemented minutiae extraction from the finger print image.


Steps involved

Image thinning.
Detection of the ridges and bifurcations.
Plotting the (x,y) coordinates which contains the minutiae points.

Cancellable Template implementation (POC) : Method 1

Proposed Method : 1

Distance calculation between the minutiae coordinates using neo4j graph database.
Implementing reverse tranformation logic.
Implemented:

Choose a reference point in the list of minutiae.
Find the distance from the reference minutiae to all other minutiae points.
