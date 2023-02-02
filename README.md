# Gpu_Kmeans_clustering
To run the program, simply rfollow the below steps:
1. Go to the project folder
2. Create a folder build (mkdir build)
3. Go inside the folder build (cd build)
4. Compile the code using cmake (cmake ..)
5. Run the generated executable file (./Kmeans)

The following command line arguments needs to be passed:
std::string inputFile <Path to the input file to perform Kmeans, can be relative to absolute>
int epochs <Maximum no. of iterations to perform to improve the centroids>
int k <Number of clusters to be formed in the data>

The output is the list of centroids of the number of clusters specified in the form of (x,y)

eg.
Command:

./K-means "../datasets/housing.csv" 1000 13

Output:

(-0.22672,0.229453)

(-0.47875,0.196979)

(0.251361,0.62856)

(-0.251535,0.478767)

(0.358126,0.318907)

(0.320568,0.842703)

(0.311832,1.11696)

(0.0197482,0.194239)

(-0.276979,0.722414)

(0.431745,0.519682)

(0.243471,0.469575)

(-0.268007,1.07198)

(0.433202,0.148779)
