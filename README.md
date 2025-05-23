# Introduction
Urban Rivers is a conservation organization, "Transforming urban waterways into wildlife sanctuaries, creating opportunities for people of all backgrounds to connect with nature in new and meaningful ways"  

Part of the project involves tracking changes in biodiversity attributable to the installation of floating wetlands.  
Volunteers (like me) have placed and maintain motion detection cameras (camera traps) along installations, natural river banks, and the existing metal retaining walls on the water way.  

Of these pictures, a HUGE majority are false positives for animals - basically any time a branch moves in the wind (all the time) there's a high likelihood that an image will be taken.  
We've tried many times to adjust the sensitivity, but this problem still remains.  

So, this workbook was developed for testing AI/Computer Vision models recently released in an attempt to filter through images for less boring labeling.  
Future work may involve fine tuning a model -- but this is a good enough starting point.  


# Resources / References
Urban Rivers based in Chicago  
https://urbanrivers.org/mission  

SpeciesNet was developed by Wildlabs and made open source by Sefan Istrate  
https://wildlabs.net/discussion/we-are-releasing-speciesnet  

The detector portion of the code was developed by Dan Morris with the AI for Earth Team - Megadetector  
https://github.com/agentmorris/MegaDetector  

### ======= To get started, clone the env file ========
> conda env create -f environment.yml



Code for notebook "run species net on kaggle" from Dan Morris.  


Speciesnet resource  
@article{gadot2024crop,
  title={To crop or not to crop: Comparing whole-image and cropped classification on a large dataset of camera trap images},
  author={Gadot, Tomer and Istrate, Ștefan and Kim, Hyungwon and Morris, Dan and Beery, Sara and Birch, Tanya and Ahumada, Jorge},
  journal={IET Computer Vision},
  year={2024},
  publisher={Wiley Online Library}
}

https://github.com/google/cameratrapai
