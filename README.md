Data:
	Matrix containing movie ratings made by users.
	Matrix is extracted from a Netflix Database.
	The matrix is sparse. (Mostly 0s)
	
Objective:
	Build a mixture model for collaborative filtering. 
	Predict all the remaining entries of the matrix.
	
Model:
	We use a mixture of Gaussians.
	Model assumes each rating profile is a sample from a mixture model.
	EM Algorithm is used to estimate the mixture from a partially observed matrix.
	
EM Algorithm:
	E-Step - softly assigns users to clusters
	M-Step - re-estimates the Gaussians
	
