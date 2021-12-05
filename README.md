Data:
	Matrix containing movie ratings made by real users.
	Matrix is extracted from a Netflix Database.
	
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
	
nbviewer link:
	https://nbviewer.org/github/OnlineDimension/gmm_recommender/blob/main/GMM.ipynb
	
