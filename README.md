# zenodo_upload
Python script to upload files to Zenodo

Usage: `python zenodo_upload.py [INPUT_JSON] [ZENODO_ACCESS_TOKEN]`

Example [INPUT_JSON]

```
{
    "author" : "Lee, Jin",
    "affiliation" : "Stanford University",
    "data" : [
        {
            "title" : "Dataset CTCF (1/2) for ENCODE-DREAM TF Binding Challenge",
            "description" : "Dataset CTCF (1/2) for ENCODE-DREAM in vivo Transcription Factor Binding Site Prediction Challenge",
            "files" : [
                "/users/leepc12/code/atac-seq-pipeline/cromwell-executions/atac/223a2529-028e-43aa-98f9-6079fa9c5d30/call-bowtie2/shard-1/execution/ENCFF641SFZ.subsampled.400.trim.merged.bam",
                "/users/leepc12/code/atac-seq-pipeline/cromwell-executions/atac/223a2529-028e-43aa-98f9-6079fa9c5d30/call-bowtie2/shard-0/execution/ENCFF341MYG.subsampled.400.trim.merged.bam"
            ]
        },
        {
            "title" : "Dataset CTCF (2/2) for ENCODE-DREAM TF Binding Challenge",
            "description" : "Dataset CTCF (2/2) for ENCODE-DREAM in vivo Transcription Factor Binding Site Prediction Challenge",
            "files" : [
                "/users/leepc12/code/atac-seq-pipeline/cromwell-executions/atac/223a2529-028e-43aa-98f9-6079fa9c5d30/call-filter/shard-0/execution/ENCFF341MYG.subsampled.400.trim.merged.nodup.bam",
                "/users/leepc12/code/atac-seq-pipeline/cromwell-executions/atac/223a2529-028e-43aa-98f9-6079fa9c5d30/call-filter/shard-1/execution/ENCFF641SFZ.subsampled.400.trim.merged.nodup.bam"
            ]
        }
    ]
}
```
