# LiCSAR-Processor
This section describes core functionality of LiCSAR system, that is used by LiCSAR FrameBatch system but can be used independently.  By  https://comet-licsar.github.io/licsar_proc/index.html#nisar-data-processing

## Dr. Milan teaches how to process
1. Login at sawitree@login.jasmin.ac.uk>> `ssh -AX sawitree@#instance.jasmin.ac.uk`
2. `lics_checker`
3. `source /gws/smf/j04/nceo_geohazards/software/mambalics/load_mambalics.rc`
4. `module list` `module avail` `module load #name` `module unload #name` `module show #name`
5. `cd $BATCH_CACHE_DIR`
6. `ls *` shows all details
7. `mkdir LiCSBAS`
8. `mv 0* 1* LiCSBAS/.`
9. `store_to_curdir.sh`
10. `licsar_make_frame.sh` >> Usage: licsar_make_frame.sh FRAME_ID [full_scale] [autodownload] [startdate] [enddate] - e.g.
11. 
12.  
