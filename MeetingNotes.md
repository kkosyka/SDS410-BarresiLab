## 2019-02-19

## Meeting Notes
### Where to go after running the sample data
   -AT has to be processed first (all the alignments are done on) so that we know what things are relative to
   -ZRF-1 is the associated signal (in relation to AT), it is the actual flag

### Manually changing bins
   -AT Wild type radius 20
   -AT You-too radius 10 

### Potential program improvements?
   -Slider to produce the best alignment? Calibration 
   -Find the best bin size? (similar to the idea of df and overfitting/underfitting)

### Caveats for now
   -Currently have to set the landmarks manually 
   -Mathematically determining the number of landmarks




## 2019-02-05

## Meeting Notes
### Big idea: qualitative data (image)---> quantitative (coordinates) ---> Statistical Analysis
   -After collecting multiple samples (fish brains), we want to quantify and standardize the data
### Data file 
   -Imgae file format:  
     -tiff: 3D   
     -hdf5: multidimentional analysis of data  
   -Store image data, 3D stacks of data
### Process
   - First, using Principal Component to adjust/align coordinates
   - Next, Using Dealtascope fit the models
   - Transfer "Cube Data" to "Point Cloud File"
### Point Cloud File
   -Model align with zebrafish brain structure  
   -Data points are wraped around the model   
   -Data points in comparison to the model  
   -Data points in orientation to the model  
   -Data move with the model  
   -Flatten the data into 2D/line in order to analyze    

-Goal:commissure align at the origin

### Sharable Data 
   -Share large data file
   -Purpose is to enable other researchers to test on our data
   -Options: github? R package?
   
### Next Step
   -Watch Morgan's video 
   -Follow up to run the program with the data
   -Transfer data to R package
   

  
