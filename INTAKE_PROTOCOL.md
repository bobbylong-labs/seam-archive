# Transcript Intake Protocol  

This document defines the rules and procedure for adding transcripts to the seam-archive repository.  

## Rules  
- All transcripts must be added in their original, unedited form.  
- No content modification, cleanup, summarization, or restructuring is permitted.  
- Each transcript belongs in exactly one version directory:  
  - transcripts/gpt-4/  
  - transcripts/gpt-5/  
  - transcripts/gpt-5.1/  
- Filenames must follow strict format:  
  YYYYMMDD-session-XX.md  

## Procedure  
1. Place the transcript in the correct version directory.  
2. Name the file using the required format.  
3. Commit directly to main with a brief commit message:  
   "Add transcript [YYYYMMDD-session-XX]"  
4. Do not modify previously committed transcripts.  
5. When a batch of transcripts is complete, reference them in RELEASES.md under the appropriate release number.  

## Purpose  
This protocol preserves provenance integrity by ensuring each transcript maintains:  
- original content  
- original structure  
- correct chronological placement  
- consistent lineage within its version
