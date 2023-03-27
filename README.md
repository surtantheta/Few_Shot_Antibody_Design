# Few_Shot_Antibody_Design

## SAbDab Data Download
```python
python ./SAbDab_Dataloader/sabdab_downloader.py --summary_file './SAbDab_Dataloader/sabdab_summary.tsv' --output_path './SAbDab_Dataloader/SAbDab/' --original_pdb 
```
## SAbDab Data Pre-processing
### Package Installation
```python
pip install Bio
```
```python
python ./SAbDab_Dataloader/download.py --summary './SAbDab_Dataloader/sabdab_summary.tsv' --fout './SAbDab_Dataloader/sab_dab_all.json' --type 'sabdab' --pdb_dir './SAbDab_Dataloader/SAbDab/'
```