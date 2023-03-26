# Few_Shot_Antibody_Design

## SAbDab Dataloader
### SAbDab Data Download
```python
python sabdab_downloader.py --summary_file './sabdab_summary.tsv' --output_path './SAbDab/' --original_pdb 
```
### SAbDab Data Pre-processing
```python
python download.py --summary './sabdab_summary.tsv' --fout './sab_dab_all.json' --type 'sabdab' --pdb_dir './SAbDab/'
```