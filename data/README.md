# QoE open dataset using VLC indicators

This open dataset the  following data:

   - Subjective rattings.
   
   - MOS scores.
   
   
  To build this dataset, a testbed is achieved in the LiSSi laboratory (http://lab.lissi.fr/) around Paris city in France. 62 
testers prticipated in the test campaign. All of them were researchers and students from different disciplines aged 19 to 41 
years  with  few  or  no  experience  with video assessment experimentation. The collected QoE IFs concerns many video 
parameters that VLC video player provides as indicator.

   

## Acknowledgement

If you use the proposed open dataset in your research., you must
   
   1- Include the link to the repository.
   
   2- Cite the following publication:
   
   @misc{dataset2017,
author = {{L}amine Amour, and {S}ami Souihi, and {M}ellouk {A}bdelhamid},
title = {{Dataset 02~: Controlled Laboratory dataset collecting You Tube QoE IFs using VLC video player. Access: }},
year = {October 2017}, 
howpublished = {\underline{ \url{https://cir.fr/qoe-dataset/xxxxxxxx}}},
}

 ## File Layout
    
 The subjective data is contained in the following files:
    
  - `mos.csv`: Per-HRC subjective MOS with 95% CI, columns:
     - `hrc-id`: Identifier of the HRC
     - `context`:	"desktop" or "laptop"
     - `mos`:	MOS score
     - `sd`:	Standard deviation of the MOS.
     - `n-tests`: Number of rattings considered for MOS
     - `ci`: 95% confidence interval
      
      

  - `ratings.csv`:  
     - `HRC-ID`: Identifier of the HRC
     - `diplay_res`: Height of display in pixels
     - `player_caching`: VLC cach value in milliseconds
     - `diplay_bitrate`: Average measured video bitrate
     - `diplay_framerate`: Average measured video framerate
     - `diplay_frame_drop`: Average measured video dropped frames
     - `diplay_audiorate`: Average measured audio rate
     - `diplay_audioloss`: Average measured audio dropped frames
     - `diplay_buff`: Buffering time
     - `context`: "desktop" or "laptop"
     - `id_user`: Subject identifier
     - `mos`: MOS score

 ## Licence
     
Copyright 2018 TinCNet group, Paris Est Créteil Uinversity.

Permission is hereby granted, free of charge, to use this dataset for non-commercial research purposes.

NO EXPRESS OR IMPLIED LICENSES TO ANY PARTY'S PATENT RIGHTS ARE GRANTED BY THIS LICENSE. THE DATASET IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATASET OR THE USE OR OTHER DEALINGS IN THE DATASET.
    
## Authors

Main developers:
- Lamine Amour (TincNet group, LiSSi Laboratory, Paris Est Créteil University) 

Contributors:
- Sami Souihi (TincNet group, LiSSi Laboratory, Paris Est Créteil University)
- Abdelhamid Mellouk (TincNet group, LiSSi Laboratory, Paris Est Créteil University)

    
