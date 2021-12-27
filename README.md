# Satellite-image-based surface reconstruction in `MicMac`
> A tutorial

- toc: true 
- badges: true
- comments: true
- categories: [jupyter] 
- image: images/chart-preview.png

## Goal 

In this tutorial we will introduce you to satellite image processing in MicMac. The goal of the exercise is to compute the surface and generate an orthohoto given a set of *modern* satellite images and their RPC geolocalisations. After setting-up MicMac and downloading the dataset, the pipeline is as follows:
  1. Tie-points extraction
  2. RPC-bundle adjustement
  3. Surface computation
    
    3.1. ***Method1***: Matching in object geometry

    3.3. ***Method2***: Matching in image geometry and fusion

<br>
```Python
Tools = ['Python', 'micmac', 'opencv','matplotlib', 'Colab Notebooks']
```

