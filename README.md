# pointCloudFusion_1

1.	Introduction
2.	Data acquisition, Preprocessing, Fusion process
2.1 Camera setup
               Technology of RealSense D435
	        Terminologies
      Checklist for camera setting
2.2 Dual camera system setup in the experiments
	      A simple stereo system for the experiment
      Perspectives from dual camera system
2.3 Data preprocessing
      Covert bag files into accessible format
      Align two videos streams
      Naming convention and system time
        Preprocessing point cloud
      Point set fusion
2.4 Down sampling
2.5 Methods
      3D rotation
      Overlapping ratio
      Fusion
2.6 Evaluation Formula
                        Unit
      RMSE
      Average group distance
      Translation error
      Rotation error
      Convergence time consumption
3.	Four algorithms, methods, discussed issues 
3.1 ICP Point-to-Point
3.2 ICP Point-to-Plane
3.3 Normal Distribution Transformation
3.4 Coherent Point Drift
3.5 ICP program parameters
4.	Experiments, Result and discussion 
         4.1 Experiments – box fusion and human pose fusion
        Box fusion experiment
       Human pose fusion experiment
4.2 Results and discussion – box fusion and human pose fusion
      Box experiment results and discussion
      Human pose experiment results and discussion
        4.3 Different ratio setting fusion results
     ICP Point-to-Plane model performance
     ICP Point-to-Point model performance
     NDT model performance
         Four models performance
4.4 Fusion under different noise settings
     Initial setting
     Experiment results
     Result demonstration
     Models performance comparison
5.	Conclusions 
References 
